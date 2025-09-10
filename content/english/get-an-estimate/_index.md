---
title: "Get An Estimate"
meta_title: ""
description: "this is meta description"
draft: false
estimate_form:
  full_name:
    label: "Full Name"
    placeholder: "John Doe"
    required: true
  email:
    id: "email"
    label: "Email"
    placeholder: "john.doe@email.com"
    required: true
  most_important_aspect:
    label: "What is the most important aspect of this job?"
    required: true
    options:
      - "Quality"
      - "Budget"
      - "Delivery Date"
  second_most_important_aspect:
    label: "What is the second most important aspect of this job?"
    required: false
    options:
      - "Quality"
      - "Budget"
      - "Delivery Date"
  budget:
    label: "What is your budget for this project?"
    placeholder: "Please provide a rough estimate of your budget"
    required: true
  material:
    label: "What material is ideal for your project to be built from?"
    required: true
    options:
      - "Hardwood"
      - "Plywood"
      - "Painted MDF"
  finish:
    label: "Natural hardwood color or stained/painted project?"
    required: true
    options:
      - "Prefer the real wood with clear finish"
      - "Prefer a stain or painted finish"
  timeline:
    label: "What is your ideal timeline for the project?"
    required: true
    options:
      - "Less than 1 week"
      - "1 to 2 weeks"
      - "2 to 3 weeks"
      - "4 or more weeks"
  delivery_installation:
    label: "Do you desire to have the project delivered, installed, or both?"
    required: true
    options:
      - "Delivered"
      - "Installed"
      - "Both"
  product:
    label: "Please give a rough estimate of the applicable dimensions if you are able:"
    list:
      - Drawers
      - Outlets
      - Shelves
      - Cabinets

  additional_comments:
    label: "Please add any additional comments that may be helpful in visualizing the project before meeting"
    placeholder: "Additional comments"
    required: false
  file_upload:
    label: "Attach any pictures, sketches, or inspiration to the email you send to us. (total size limit 5MB)"
    required: false

  
---


