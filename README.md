# User-Data-Validation-Text-Analysis-System

## User Data Validation & Text Analysis System

## Overview

This Python project is a text processing module for validating and analyzing user data.The system receives raw string inputs (name, email, age), cleans the data, validates emails and age, identifies invalid records, and produces a summary report including domain statistics.

## Features

# Data Cleaning
*Removes extra spaces
*Converts names to title case
*Converts emails to lowercase

# Email Validation
*Exactly one '@' symbol
*At least one '.' after '@'
*Should not start or end with '@'

# Age Validation
*Converts age to integer
*Checks eligibility (>=18)

# Invalid Record Identification
*Detects missing names
*Invalid emails
*Underage users (<18)

# Summary Report
*Total records
*Valid users
*Invalid users
*Eligible and underage users

# Bonus Feature
*Extracts email domains
*Counts users per domain
