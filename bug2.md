# bug2

## 1
Test ``||input:hi||`` and **Motor** maybe.

```blocks
input.onButtonPressed(Button.A, function () {
    for (let index = 0; index < 4; index++) {
        Kitronik_Move_Motor.move(Kitronik_Move_Motor.DriveDirections.Forward, 30)
        basic.pause(1000)
        Kitronik_Move_Motor.spin(Kitronik_Move_Motor.SpinDirections.Right, 30)
        basic.pause(250)
        Kitronik_Move_Motor.stop()
    }
})
```

## 2
Thanks for checking this out!

```package
loops
input
kitronik-move-motor=github:KitronikLtd/pxt-kitronik-move-motor
```