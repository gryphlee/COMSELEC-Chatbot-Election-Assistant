# COMSELEC-Chatbot-Election-Assistant

COMSELEC Chatbot: Election Assistant

Case Study & System Documentation
by Lee Natividad – AI Agent Engineer | AI Specialist

1. System Overview

The COMSELEC Chatbot is an AI-powered election assistant designed for student elections. Built using Jotform AI Agent Builder, the system simulates the functions of a Commission on Elections (COMSELEC) office by automating voter registration, candidate validation, election FAQs, and document handling.

It ensures a transparent, efficient, and digital-first approach to student elections, minimizing manual errors and delays while providing 24/7 accessibility to students and election officers.

2. Objectives

The COMSELEC Chatbot project addresses common challenges in school elections:

Manual Overhead – Candidate and voter verification usually require multiple manual steps.

Data Integrity – Preventing duplicate voters and validating candidate qualifications.

Accessibility – Providing 24/7 election-related assistance to students.

Transparency – Ensuring documents (resolutions, memos, MOMs) are easy to store and retrieve.

Automation – Streamlining the registration and approval process.

3. Core Features
Candidate Registration

GPA/Credit validation (via form calculation logic).

Transcript OCR upload for academic verification.

Facial recognition for student ID photos (via AI integration).

Automated qualification status (Eligible / Not Eligible).

Voter Registration

SMS verification to confirm unique voters.

Selfie & ID biometric matching to prevent impersonation.

Duplicate checking against existing registrants.

Secure voter database creation.

Information Assistance

Chat-based FAQ system about election rules, schedules, and guidelines.

Automated responses for “How do I register?”, “When are the elections?”, etc.

Integration of election resolutions, memos, and announcements.

Document Management

Secure repository for election-related files:

Resolutions

Memos

Minutes of Meetings (MOMs)

Project Proposals

Searchable and retrievable by COMSELEC officers.

Approval Workflow

Integration with Jotform Approval Flows for step-by-step validation:

Candidate qualification review

Voter eligibility approval

Document endorsements

Accessibility

Available in Chat mode (website/social media embed).

Available in Call mode for phone-based support.

Deployable as a Standalone Web App (PWA installable).

4. System Architecture
[Student User] 
   ↓ Chat / Call
[COMSELEC Chatbot AI Agent] 
   ↓
[Registration & Validation Engine] 
   ↓
[Approval Flow + Document Management] 
   ↓
[COMSELEC Database / Sheets / Automation Tools]


Frontend: Jotform AI Agent (Standalone, Chat, Call)

Backend: Jotform Forms + Approval Workflows

Data Flow:

Student registers as candidate or voter

AI + form logic validate requirements

COMSELEC officers review via approval workflow

Data stored in databases, accessible anytime

5. User Experience (UX) Flow

Student opens chatbot → selects Candidate Registration or Voter Registration.

Chatbot guides the student through requirements.

AI validation: GPA, ID, and duplicate checking.

If qualified, student receives confirmation and election ID.

If candidate, profile is sent to COMSELEC officers for approval.

Election docs (memos, resolutions) are accessible through chatbot queries.

6. Deployment Channels

Standalone Web App (Jotform-hosted)

Chatbot Embed (school website, FB Messenger, or student portal)

Call Integration (IVR-style election assistant)

Progressive Web App (installable mobile version)

7. Benefits

Transparent and efficient election management

Automated candidate and voter validation

Secure and organized document handling

Accessible 24/7 to students and officers

Reduces human errors and manual workload

8. Future Enhancements

Blockchain-based vote tracking for tamper-proof elections

AI-powered election analytics (turnout predictions, candidate visibility)

Real-time election results announcement module

Multilingual support for diverse student bodies

9. Screenshots & Visuals

(to include screenshots of chatbot interface, approval workflow, and registration forms)

10. Conclusion

The COMSELEC Chatbot redefines how student elections can be conducted by combining AI, automation, and secure workflows.

By providing candidate registration, voter verification, document management, and 24/7 election assistance, the chatbot serves as a digital election officer — ensuring transparency, efficiency, and fairness.

This project demonstrates the power of AI-driven governance systems and provides a scalable model that schools and universities can adopt for modern, tech-enabled elections.
