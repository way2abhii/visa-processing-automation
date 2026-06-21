# visa-processing-automation
Built an AI-powered visa processing automation platform using n8n, Twilio, Google Sheets, LlamaParse, and Groq LLM. The system automates applicant onboarding, passport document collection, OCR extraction, case management, payment tracking, and WhatsApp-based status notifications through an event-driven workflow architecture.

# Visa Processing Automation using n8n

## Overview

An end-to-end visa processing workflow built with n8n.

Features:

- WhatsApp chatbot using Twilio
- User onboarding
- Google Sheets CRM
- Passport upload handling
- OCR using LlamaParse
- Passport number extraction using LLM
- Payment status tracking
- Automated WhatsApp notifications

## Workflow

1. User sends WhatsApp message
2. User record created in Google Sheets
3. Passport document requested
4. Passport uploaded
5. LlamaParse extracts document content
6. LLM extracts passport number
7. Case created
8. Payment status tracked
9. Visa status updates sent automatically

## Tech Stack

- n8n
- Twilio WhatsApp API
- Google Sheets
- LlamaParse
- Groq LLM
- OpenAI OSS 120B

## Screenshots

(Add screenshots here)

## Workflow Import

Import `workflow.json` into n8n.

