# Yandex Samokat — Test Design

## 📋 Overview

Test design was performed as part of the Yandex Practicum diploma project for the Yandex Samokat web application.

The goal was to identify valid and invalid input conditions and verify the boundaries defined by the requirements.

## 🧪 Test Design Techniques

The following techniques were used:

* Equivalence Partitioning
* Boundary Value Analysis
* Positive testing
* Negative testing

## 📝 Tested Fields

### Name

Tested:

* Valid values
* Minimum length
* Maximum length
* Values exceeding the maximum length
* Numbers
* Special characters
* Hyphen
* Dash
* Spaces
* Empty value

### Surname

Tested:

* Valid values
* Minimum length
* Maximum length
* Values exceeding the maximum length
* Numbers
* Special characters
* Empty value

### Address

Tested:

* Valid values
* Minimum length
* Maximum length
* Values exceeding the maximum length
* Numbers
* Invalid characters
* Hyphen
* Spaces
* Empty value

### Phone Number

Tested different formats and boundary values for:

* `+7` format
* `8` format
* Minimum allowed length
* Maximum allowed length
* Values below the minimum
* Values above the maximum
* Letters
* Special characters
* Empty value

### Delivery Date

Tested:

* Valid future dates
* Current date
* Previous dates
* Empty value

### Rental Period

Tested:

* Minimum rental period
* Maximum rental period
* Values within the allowed range
* Unselected value

### Scooter Color

Tested:

* One selected color
* Both colors selected
* No color selected

### Comment

Tested:

* Valid text
* Maximum allowed length
* Text exceeding the maximum length
* Invalid characters
* Spaces
* Empty value

## 📊 Test Results

The test design included positive and negative test cases with test data located both inside equivalence classes and on their boundaries.

Failed test cases were linked to corresponding bug reports.

## 🎯 Result

The test design helped identify validation defects and verify how the application handled boundary and invalid input values.

