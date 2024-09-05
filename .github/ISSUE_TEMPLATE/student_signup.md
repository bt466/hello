---
name: Student Sign-Up
about: Signing up to this repository
title: "[SIGN-UP] <Your Full Name>, <Your SIS ID>"
labels: 'sign-up'
assignees: ''
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!
  - type: input
    id: contact
    attributes:
      label: Contact Details
      description: How can we get in touch with you if we need more info?
      placeholder: ex. email@example.com
    validations:
      required: false
  - type: textarea
    id: what-happened
    attributes:
      label: What happened?
      description: Also tell us, what did you expect to happen?
      placeholder: Tell us what you see!
      value: "A bug happened!"
    validations:
      required: true
---

### Student Information

**Full Name**:  
Provide your full name (First Name, Last Name).

**SIS ID**
Provide your SIS ID. 

**Email Address**:  
Provide the email address you've used on GitHub

**GitHub Username**:  
Provide your GitHub username (for submitting assignments and collaborating on projects).
