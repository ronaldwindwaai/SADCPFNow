# 🇸🇿 SADC PF Now – Official Application of the SADC Parliamentary Forum

A mobile-first application built with **Flutter** and **Bloc architecture**, designed to streamline access to **news, events, plenary sessions, committee information, and internal collaboration** for Members of Parliament, Speakers, and Secretariat staff across the 15 SADC member states.

---

## 📱 Key Modules & Features

### 🏠 1. Homepage
- Displays latest news & events
- Highlights upcoming meetings and deadlines
- Quick links to key modules (e.g. Committees, Documents)

### 🏛️ 2. Plenary Assembly
- **Agenda & Documents**: Current and historical records
- **Sessions**: Calendar, summaries, and optional livestream integration
- **Decisions**: Policy outcomes and resolutions
- **Executive Committee Reports**: Direct access to oversight documents

### 👥 3. Executive Committee
- Structure: 7 Speakers + 7 MPs (2-year tenure)
- Sub-Committees:
  - Finance
  - HR
  - Legal
  - Parliamentary Business
- Tools:
  - Budget tracking
  - Action plan submissions
  - Meeting calendar and document hub

### 🧭 4. Standing Committees
- List and detail view for each Committee:
  - Gender, Youth, and Women Advancement
  - Trade & Investment
  - Food & Agriculture
  - Human Rights & Democratisation
  - Human & Social Development
- Member directory with country, role, and contact details
- Meeting minutes, ToRs, reports, and notifications

### 📚 5. Regional Parliamentary Model Laws Oversight Committee
- Draft and approved Model Laws
- Oversight reports on implementation
- Membership list of oversight team

### 🧑‍💼 6. Secretariat
- Staff directory with roles and contact info
- Admin-only tools:
  - Upload documents
  - Assign user roles and committee permissions
  - Access all workspaces

---

## 👤 User Roles & Access

| Role                   | Access                                                                 |
|------------------------|------------------------------------------------------------------------|
| Secretariat Staff      | Full access, edit/upload across all modules                            |
| Speakers               | Executive Committee + Sub-Committees only                              |
| MPs                    | Assigned Standing Committee(s)                                         |
| Management Board       | Executive access + high-priority alerts                                |

---

## 🛠️ Technical Architecture

- **Frontend**: Flutter (cross-platform), Bloc for predictable state management
- **Backend**: Firebase or custom API (planned)
- **Data Storage**: Secure Firestore or encrypted REST-based endpoints
- **Security**:
  - Role-Based Access Control (RBAC)
  - Two-Factor Authentication (2FA)
  - Encrypted document storage
  - Audit logs for sensitive operations

---

## 🧱 Committee Membership Module (Example)

Implemented with `flutter_bloc` and includes:

- Committee Directory
- Member Lists with filters
- Member Profiles with roles and contributions
- Document uploads and linked documents per committee
- Internal comment threads (optional for private collaboration)
- Admin Panel for member management (incl. bulk import via CSV)

---

## 🔁 Integration Features

- **Calendar Sync** (Google, Outlook)
- **Notifications** for updates and new uploads
- **Document Repository** with metadata filters
- **Internal Forums** for secure committee discussions

---

## ▶️ Getting Started

### 🔧 Prerequisites

- Flutter SDK >= 3.7.0
- Dart >= 3.7.0
- Android Studio or VS Code with Flutter plugins

### 📥 Install

```bash
git clone https://github.com/ronaldwindwaai/SADCPFNow.git
cd SADCPFNow
flutter pub get
flutter run
