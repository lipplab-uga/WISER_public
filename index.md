
## Coming Soon!

Test text.

| Tables        | Test           | Text  |
| ------------- |:-------------:| -----:|
| samp 1      | value 1 | x |
| samp2       | value 2 | y |
| samp3       | value 3 | z |


### {.tabset}

#### tab 1
test

#### tab 2
_test_


### First tabs

{% tabs log %}

{% tab log php %}
```php
var_dump('hello');
```
{% endtab %}

{% tab log js %}
```javascript
console.log('hello');
```
{% endtab %}

{% tab log ruby %}
```javascript
pputs 'hello'
```
{% endtab %}

{% endtabs %}

### Second tabs

{% tabs data-struct %}

{% tab data-struct yaml %}
```yaml
hello:
  - 'whatsup'
  - 'hi'
```
{% endtab %}

{% tab data-struct json %}
```json
{
    "hello": ["whatsup", "hi"]
}
```
{% endtab %}

{% endtabs %}
