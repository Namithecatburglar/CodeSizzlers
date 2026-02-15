# CodeSizzlers
AI For Bharath
# Requirements Document
## AI-Powered Opportunity Intelligence System for Students

### 1. Project Overview
Students across India miss scholarships, internships, competitions, and career opportunities due to fragmented information sources, language barriers, and lack of personalized guidance. This system aims to centralize opportunity discovery and deliver personalized, explainable recommendations using AI.

---

### 2. Problem Statement
- Opportunity information is scattered across 1000+ unstructured sources (PDFs, websites, portals).
- Existing platforms rely on keyword search and manual listings.
- Rural and low-income students lack timely, relevant, and accessible information.
- Missed deadlines lead to permanent loss of opportunities.

---

### 3. Goals & Objectives
- Centralize opportunity discovery into a single intelligent platform.
- Personalize opportunity recommendations for each student.
- Prevent missed deadlines through smart alerts.
- Ensure inclusive access across languages, devices, and bandwidth conditions.

---

### 4. Functional Requirements

#### 4.1 User Management
- User registration and authentication.
- Profile creation including:
  - Academic background
  - Skills and interests
  - Location
  - Career goals
- Profile editing and preference management.

#### 4.2 Opportunity Ingestion
- Automatic data ingestion from:
  - Government portals
  - University websites
  - Company career pages
  - PDFs and announcements
- Support for unstructured data formats.
- Multi-language content extraction.

#### 4.3 NLP Extraction Engine
- Extract structured fields:
  - Eligibility criteria
  - Deadlines
  - Benefits / stipend
  - Location
  - Category (scholarship, internship, competition)
- Validate and normalize extracted data.

#### 4.4 Recommendation Engine
- Match opportunities to student profiles.
- Use both:
  - Content-based filtering
  - Collaborative filtering
- Generate relevance scores (0–100).
- Continuously improve using user interaction feedback.

#### 4.5 Explainable AI
- Provide explanations for recommendations:
  - Why this opportunity is suggested
  - Matching factors used
- Build user trust and transparency.

#### 4.6 Alerts & Tracking
- Deadline reminders.
- Saved opportunity tracking.
- Weekly “Missed Opportunity Insights”.
- Notifications via:
  - Web
  - Mobile
  - WhatsApp
  - SMS

#### 4.7 Accessibility & Inclusion
- Support for 10+ Indian languages.
- Low-bandwidth mode (2G/3G).
- Screen reader compatibility.
- Feature-phone access via SMS.

---

### 5. Non-Functional Requirements

#### 5.1 Performance
- API response time < 100ms.
- Page load time < 3 seconds on 3G.

#### 5.2 Scalability
- Handle millions of users.
- Support ingestion from 1000+ sources.
- Auto-scale based on traffic.

#### 5.3 Security
- End-to-end encryption.
- Secure authentication and authorization.
- GDPR-compliant data handling.

#### 5.4 Reliability
- 99.9% uptime.
- Fault-tolerant ingestion pipeline.

---

### 6. Constraints
- Budget limitations for cloud resources.
- Accuracy depends on source data quality.
- Initial cold-start problem for recommendations.

---

### 7. Success Metrics
- ≥95% recommendation relevance accuracy.
- ≥80% reduction in missed opportunities.
- ≥85% user satisfaction.
- ≥1 million students reached.

---

### 8. Out of Scope (MVP)
- Manual opportunity submission.
- Paid premium features.
- Enterprise dashboards.
