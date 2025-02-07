## Testing Guidelines

1. **Unit Tests**
   - All new features must include unit tests
   - Use Google Test framework
   - Place tests in `tests/` directory
   - Name tests `*_test.cpp`

2. **Test Structure**
   ```cpp
   TEST(ClassNameTest, FunctionName_Scenario_ExpectedBehavior) {
       // Arrange
       // Act
       // Assert
   }
   ```

## Documentation

1. **Code Documentation**
   - Document all public APIs
   - Use clear and concise comments
   - Update README.md when needed
   - Include examples for new features

2. **Documentation Style**
   ```cpp
   /**
    * Brief description
    *
    * @param param_name Description of parameter
    * @return Description of return value
    * @throws Description of exceptions
    */
   ```

## Issue Reporting

1. **Bug Reports**
   - Use the bug report template
   - Include minimal reproduction steps
   - Specify environment details
   - Include error messages and logs

2. **Feature Requests**
   - Use the feature request template
   - Explain the use case
   - Describe expected behavior
   - Provide examples if possible

## Review Process

1. All PRs require at least one review
2. Address all review comments
3. Keep PR scope focused
4. Maintain clear communication

## Questions?

Feel free to:
- Open a discussion
- Contact maintainers directly

Thank you for contributing to Gloom!
