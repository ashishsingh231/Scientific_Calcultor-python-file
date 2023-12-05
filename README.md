# Scientific_Calcultor-python-file
# Parent class
class Calculator:
    def add(self, num1, num2):
        return num1 + num2

    def subtract(self, num1, num2):
        return num1 - num2

    def multiply(self, num1, num2):
        return num1 * num2

    def divide(self, num1, num2):
        if num2 != 0:
            return num1 / num2
        else:
            return "Error: Division by zero"

# Child class
class ScientificCalculator(Calculator):
    def power(self, num1, num2):
        return num1 ** num2
