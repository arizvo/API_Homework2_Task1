Feature: Smoke Test

This is a demo version of the PlaceLab application that is able to get information from websites.
This test verifies that a user is able to log in with their account credentials and create a Data Extraction Report.

Scenario: Validate that the user can log in and create a Data Extraction Report.

Given the user has an account for the application

When the user goes to create a report
And the user enters all necessary data

Then the Data Extraction Report should be created