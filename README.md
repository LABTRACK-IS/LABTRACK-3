# LabTrack v3 - Stability Pass

Third iteration of LabTrack imported from labtrack 3 on 2026-11-19.

This is a stability and hygiene pass over the v2 baseline. Not a feature release.

## Snapshot

- Backend controllers: 29
- Backend C# files: 459
- Frontend TS/TSX files: 71

## Changes in v3 (vs v2)

### Backend

- Modified files: 29
- New files: 0
- Fixed Compile Include directives (CS0101)

### Frontend

- Modified files: 15
- New files: 2

## Focus of this iteration

1. Project file hygiene - removed stray Compile Include directives
2. Tree cleanliness - removed bak and cleanup artifacts
3. Build verification - both backend and frontend checked

## Controllers in this build

AiAssistant, Analytics, Asset, Audit, Auth, ChainOfCustody, Communication, Financial, IdempotencyRecords, InstructorCommunication, Laboratories, Maintenance, MaintenanceRecord, MaintenanceRecords, Network, NetworkIncident, NetworkInfo, Notification, PcUsage, ProblemReport, QrAdmin, Qr, QrSession, RepairTicket, Replacement, ReplacementRecord, Reservation, Users, Workstations

## Quick start

Backend:

    cd backend/LabTrack.CSharp/src/LabTrack.Api
    dotnet run

Frontend:

    cd frontend
    npm install
    npm run dev

URLs:

- Frontend: http://localhost:3000
- Swagger: http://localhost:5000/swagger
- Health: http://localhost:5000/health/live

---

Generated: 2026-11-19 03:13:50
