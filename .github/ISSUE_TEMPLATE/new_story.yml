name: User Story
description: Submit a new user story for the product backlog.
title: "User Story: "
labels: ["story"]
body:
  - type: markdown
    attributes:
      value: |
        **Please provide details for the user story below:**

  - type: input
    id: user-role
    attributes:
      label: User/Role
      description: Define the type of user or role this story is for.
      placeholder: e.g. "Registered User", "Admin", "Visitor"
    validations:
      required: true

  - type: textarea
    id: desire
    attributes:
      label: Desire/Need
      description: Clearly describe what the user wants to achieve.
      placeholder: e.g. "I want to be able to reset my password"
    validations:
      required: true

  - type: textarea
    id: benefit
    attributes:
      label: Benefit/Value
      description: Explain the value or benefit this provides to the user.
      placeholder: e.g. "So that I can regain access to my account even if I forget my password"
    validations:
      required: true

  - type: textarea
    id: technical-note
    attributes:
      label: Technical Note/Reference
      description: Add technical instructions or refrence to scope or library that should be used in this story.
      placeholder: e.g. "The API endpoint to request the OTP should include an optional device-hash to be compitable with the Mobile App V2"

  - type: textarea
    id: acceptance-criteria
    attributes:
      label: Acceptance Criteria
      description: List the criteria that will be used to determine whether the user story is implemented correctly.
      placeholder: |
        1. User can click on 'Forgot Password?' link
        2. User should receives reset link via email
        3. User can resets password using the link
    validations:
      required: true

  - type: dropdown
    id: priority
    attributes:
      label: Priority
      description: How critical is this user story?
      options:
        - Blocker
        - Critical
        - Normal
        - Low
    validations:
      required: true
