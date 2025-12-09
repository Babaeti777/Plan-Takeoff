# Tests Directory

This directory contains all test files for Plan-Takeoff.

## Test Structure

Tests are organized to mirror the source code structure:

- **Unit Tests**: Test individual functions and components
- **Integration Tests**: Test interactions between components
- **E2E Tests**: End-to-end testing of complete workflows

## Running Tests

(Instructions will be added once the testing framework is selected)

## Writing Tests

### Best Practices

1. Write clear, descriptive test names
2. Follow the Arrange-Act-Assert pattern
3. Test both success and failure cases
4. Keep tests independent and isolated
5. Aim for high coverage but focus on critical paths

### Test Naming Convention

```
test_<function_name>_<scenario>_<expected_result>
```

Example: `test_create_project_with_valid_data_returns_success`

## Coverage Goals

- Unit tests: Aim for >80% coverage
- Critical paths: 100% coverage
- Integration tests: Cover all major workflows
