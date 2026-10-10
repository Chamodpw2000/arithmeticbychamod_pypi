# arithmeticbychamod

A tiny arithmetic library built to learn Python packaging.

## Install

    pip install arithmeticbychamod

## Usage

    from arithmeticbychamod import add, subtract, multiply, divide

    add(2, 3)        # 5
    subtract(5, 3)   # 2
    multiply(4, 3)   # 12
    divide(10, 2)    # 5.0
    power(2, 3)      # 8

`divide` raises `ZeroDivisionError` if the second argument is 0.