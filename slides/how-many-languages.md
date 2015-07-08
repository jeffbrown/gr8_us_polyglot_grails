##  How Many Languages?


```
// grails-app/controllers/demo/DemoController.groovy

class DemoController {

    def mathHelper

    def add(int x, int y) {
        def sum = mathHelper.add(x, y)

        render "The sum of $x and $y is $sum"
    }
}
```
