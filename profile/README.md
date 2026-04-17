<div align="center">

<img src="../assets/banner.png" alt="AURA Eyes Banner" />

### AI Understanding Retinal Analysis 👁️

<p>
    <img src="https://img.shields.io/badge/Project-SP26SE025-004D40?style=for-the-badge&logo=databricks&logoColor=white" alt="Project Code Badge" />
    <img src="https://img.shields.io/badge/Domain-Retinal%20Screening-00695C?style=for-the-badge&logo=googlefit&logoColor=white" alt="Domain Badge" />
    <img src="https://img.shields.io/badge/Status-Active%20Development-00897B?style=for-the-badge&logo=activitypub&logoColor=white" alt="Status Badge" />
</p>

<p>
    <a href="https://github.com/AuraEyesOrg/AuraEyes_BE"><img src="https://img.shields.io/badge/Backend-.NET_8-004D40?style=for-the-badge&logo=dotnet&logoColor=white" alt="Backend Repository" /></a>
    <a href="https://github.com/AuraEyesOrg/AuraEyes_FE"><img src="https://img.shields.io/badge/Frontend-React_Vite-00695C?style=for-the-badge&logo=react&logoColor=white" alt="Frontend Repository" /></a>
    <a href="https://github.com/AuraEyesOrg/AURA_AI"><img src="https://img.shields.io/badge/AI_Model-PyTorch-00897B?style=for-the-badge&logo=pytorch&logoColor=white" alt="AI Repository" /></a>
    <a href="../../docs/Register.md"><img src="https://img.shields.io/badge/Project%20Profile-Registration-004D40?style=for-the-badge&logo=readme&logoColor=white" alt="Project Registration" /></a>
</p>

</div>

---

## Roadmap (Lộ trình phát triển)

| Phase | Duration | Focus Area |
| --- | --- | --- |
| **1: Kickoff & Specifications** | 01/01 - 15/01/2026 | Project Scope, Architecture Design, Workflow Definition |
| **2: Core Build** | 16/01 - 15/03/2026 | API Development, UI/UX Implementation, AI Model Initialization |
| **3: Integration** | 16/03 - 15/04/2026 | AI-Assisted Diagnosis Integration, End-to-End Testing |
| **4: Finalization** | 16/04 - 30/04/2026 | Performance Audit, Documentation, Release Polishing |

---

## What It Does (Giới thiệu dự án)

**AURA Eyes** is a state-of-the-art retinal vascular screening platform designed to empower clinical reviews through AI. The system streamlines medical workflows, enabling teams to transition from image capture to diagnostic decisions with unprecedented efficiency.

The system is engineered to achieve three primary outcomes:
- **Accelerate** retinal screening through high-precision AI-assisted analysis.
- **Optimize** interactions between Patients, Clinics, and Ophthalmologists.
- **Ensure** medical workflows remain auditable, secure, and strictly role-based.

---

## Key Capabilities (Tính năng cốt lõi)

### Clinical Screening (Sàng lọc lâm sàng)
- **Retinal Image Upload:** Support for high-resolution medical imaging review.
- **AI-Assisted Diagnostics:** Generation of Heatmaps and explanatory results for rapid screening.
- **Professional Validation:** Final diagnosis confirmation and adjustment by certified Ophthalmologists.

### Patient Journey (Trải nghiệm bệnh nhân)
- **Secure Access:** Authentication via OTP and Google OAuth 2.0.
- **Seamless Booking:** Direct appointment scheduling and consultation requests.
- **Health Tracking:** Real-time screening results tracking and post-diagnosis support.

### Professional Workflow (Quy trình chuyên gia)
- **Credential Verification:** Strict validation of Ophthalmologist medical licenses.
- **Case Management:** Efficient dashboard for availability control and clinical case review.
- **Tele-Consultation:** Secure real-time chat and collaboration tools for diagnostic flows.

### Admin & Organizational Control (Quản trị hệ thống)
- **Institutional Management:** Approval and activation of Clinic/Hospital accounts.
- **Financial Oversight:** Billing automation, revenue sharing, and operational reporting.

---

## Repository Map (Danh mục Repository)

### Backend Services ([AuraEyes_BE](https://github.com/AuraEyesOrg/AuraEyes_BE))

![.NET 8](https://img.shields.io/badge/.NET_8-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![SignalR](https://img.shields.io/badge/SignalR-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MediatR](https://img.shields.io/badge/MediatR-25C2A0?style=flat-square&logo=dotnet&logoColor=white) ![Serilog](https://img.shields.io/badge/Serilog-9A334E?style=flat-square&logo=nuget&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)

The Core API manages business logic, Role-Based Access Control (RBAC), clinic integrations, and scheduling. Built with **Clean Architecture** for maximum scalability and security.

### Frontend Portal ([AuraEyes_FE](https://github.com/AuraEyesOrg/AuraEyes_FE))
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Vite](https://img.shields.io/badge/Vite-B73BFE?style=flat-square&logo=vite&logoColor=FFD62E) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) ![Zustand](https://img.shields.io/badge/Zustand-443E38?style=flat-square) ![React Query](https://img.shields.io/badge/React_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white) ![React Hook Form](https://img.shields.io/badge/React_Hook_Form-EC5990?style=flat-square&logo=reacthookform&logoColor=white) ![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white) ![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat-square&logo=axios&logoColor=white) ![i18next](https://img.shields.io/badge/i18next-26A69A?style=flat-square&logo=i18next&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) ![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)

The User Interface platform provides a specialized dashboard for Ophthalmologists and a responsive portal for Patients, featuring a high-performance **Retinal Imaging Viewer**.

### [AI Engine (AURA_AI)](https://github.com/AuraEyesOrg/AURA_AI)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=FastAPI&logoColor=white)

Handles Machine Learning workloads, including **Retinal Vessel Segmentation**, anomaly detection, and diagnostic Heatmap generation to accelerate clinical review.

---

## System Flow (Kiến trúc hệ thống)

```mermaid
graph TD
    Client[Client / Web Browser]
    
    subgraph "AuraEyes FE (React/Vite)"
        UI[User Interface]
        Viewer[Retinal Image Viewer]
    end
    
    subgraph "AuraEyes BE (.NET 8)"
        API[API Gateway & Controllers]
        Auth[Authentication & Security]
        Logic[Business Logic & Services]
        DB[(PostgreSQL Database)]
    end
    
    subgraph "AURA AI (Python)"
        AI_API[FastAPI Interface]
        Model[PyTorch Segmentation Model]
    end
    
    Client <-->|HTTPS/WSS| UI
    UI <-->|REST API| API
    Viewer -->|DICOM / Images| API
    
    API <--> Auth
    API <--> Logic
    Logic <--> DB
    
    Logic <-->|HTTP / Request| AI_API
    AI_API <--> Model
```

---

## Demo Video (Trải nghiệm tính năng)

<div align="center">

<video width="100%" controls>
  <source src="https://github.com/user-attachments/assets/4fac4b26-d89d-4199-920f-80e81fc7467b" type="video/mp4">
  Trình duyệt của bạn không hỗ trợ thẻ video.
</video>
<br/>
<em>(Video Demo - Trải nghiệm các tính năng cốt lõi của AURA Eyes)</em>

</div>

---

## Team (Đội ngũ dự án)

### Supervisors (Giảng viên hướng dẫn)
| Role | Name |
| --- | --- |
| **Main Supervisor** | Nguyễn Văn Chiến |
| **Co-Supervisor** | Trương Hoàng Vinh |

### Students (Sinh viên thực hiện)

<table align="center">
  <tr>
    <td align="center" width="25%">
      <img src="https://avatars.githubusercontent.com/u/165766167?v=4" width="120px;" height="120px;" alt="Hoàng Quốc An" style="border-radius: 50%; object-fit: cover;"/><br />
      <b>Hoàng Quốc An</b><br />Leader<br />
      <a href="mailto:anhqse181520@fpt.edu.vn">anhqse181520@fpt.edu.vn</a>
    </td>
    <td align="center" width="25%">
      <img src="https://avatars.githubusercontent.com/u/156297768?v=4" width="120px;" height="120px;" alt="Trần Đình Thịnh" style="border-radius: 50%; object-fit: cover;"/><br />
      <b>Trần Đình Thịnh</b><br />Member<br />
      <a href="mailto:thinhtdse181531@fpt.edu.vn">thinhtdse181531@fpt.edu.vn</a>
    </td>
    <td align="center" width="25%">
      <img src="https://avatars.githubusercontent.com/u/153256952?v=4" width="120px;" height="120px;" alt="Đào Công An Phước" style="border-radius: 50%; object-fit: cover;"/><br />
      <b>Đào Công An Phước</b><br />Member<br />
      <a href="mailto:phuocdcase180581@fpt.edu.vn">phuocdcase180581@fpt.edu.vn</a>
    </td>
    <td align="center" width="25%">
      <img src="https://avatars.githubusercontent.com/u/157226403?v=4" width="120px;" height="120px;" alt="Nguyễn Việt" style="border-radius: 50%; object-fit: cover;"/><br />
      <b>Nguyễn Việt</b><br />Member<br />
      <a href="mailto:vietnse180672@fpt.edu.vn">vietnse180672@fpt.edu.vn</a>
    </td>
  </tr>
</table>

---

## Project Identity (Thông tin định danh)

| Item | Value |
| --- | --- |
| **Project Code** | SP26SE025 |
| **Full Name** | System for Retinal Vascular Health Screening |
| **Vietnamese Name** | Hệ Thống Sàng Lọc Sức Khỏe Mạch Máu Võng Mạc |
| **Abbreviation** | AURA Eyes |
| **Duration** | 01/01/2026 - 30/04/2026 |

---

## References
- [Project Registration Form](../../docs/Register.md)
- [Backend Documentation](../../README.md)
- [Frontend Documentation](https://github.com/AuraEyesOrg/AuraEyes_FE/blob/develop/README.md)

<div align="center">
<sub>Built with ❤️ by <b>AURA Team</b> in HCMC. © 2026</sub>
</div>
