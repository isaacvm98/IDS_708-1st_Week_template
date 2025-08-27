# IDS 706 Python Template

A simple Python template project for IDS 706 Data Engineering Systems course with automated testing and CI/CD pipeline.

## Project Description

This template includes basic Python functions with comprehensive testing setup. It demonstrates best practices for Python development including code formatting, linting, and automated testing with GitHub Actions.

## Setup Instructions

1. Clone the repository:
```bash
git clone <your-repository-url>
cd IDS_708-1st_Week_template
```

2. Install dependencies:
```bash
make install
```

3. Run all checks:
```bash
make all
```

## Usage Examples

The project includes sample functions in `hello.py`:

```python
from hello import say_hello, add

# Greet a student
greeting = say_hello("Annie")
print(greeting)
# Output: Hello, Annie, welcome to Data Engineering Systems (IDS 706)!

# Add two numbers
result = add(2, 3)
print(result)
# Output: 5
```

## Available Commands

- `make install` - Install dependencies
- `make format` - Format code with Black
- `make lint` - Check code with flake8
- `make test` - Run tests with pytest
- `make all` - Run install, format, lint, and test