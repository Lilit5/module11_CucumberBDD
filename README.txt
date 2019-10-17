Magento testing tool

Magento is an open-source e-commerce platform written in PHP. This tool is designed to test Magento basic functionality.

Getting Started
* Clone this repository
* npm install to install all required dependencies


Run Tests
To run tests:
1. run 'npm run test' command
    If you want to run a test by its name then:
        * run 'npm run test -- --tag "@<test name>"' command (available tags are @login @createProduct @all)

Changes added to the project according to the module 11 home task

1. Implemented test framework based on protractor-cucumber-framework.
2. Added 2 scenarions, one with outline.
3. Added report generation mechanism (generating reports in json and html formats).
4. Added the ability to run Scenarios separately by using tags
