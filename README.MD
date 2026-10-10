# ESEP Grade Calculator

This library is a simple utility to calculate your grades that works by computing the average grade for each type of grade (assignments, exams, and essays). Then, the final grade is computed by summing the average of each kind multiplied by their respective weights and then the numerical grade is converted to a letter grade based on a grading scale.

Runtime requirements:
Golang 1.24+

Files:
grade_calculator.go contains the core logic with definitions and calculation functions
grade_calculator_test.go contains unit tests to assess calculation accuracy


Run unit tests:
```
cd grade_calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```