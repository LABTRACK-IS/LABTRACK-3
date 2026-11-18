# CHANGELOG - v3 vs v2

Auto-generated comparison between v2 (labtrack 2) and v3 (labtrack 3).

Generated: 2026-11-19 03:13:50

## Summary

| Area | Modified | Added |
|------|----------|-------|
| Backend | 29 | 0 |
| Frontend | 15 | 2 |

## Backend Changes

- Total C# files: 459
- Modified since v2: 29
- New files since v2: 0
- Controllers registered: 29

### Top backend modifications

- backend\LabTrack.CSharp\src\LabTrack.Api\Controllers\AiAssistantController.cs
- backend\LabTrack.CSharp\src\LabTrack.Api\Controllers\ControllerServiceBridgeExtensions.cs
- backend\LabTrack.CSharp\src\LabTrack.Api\Controllers\PcUsageController.cs
- backend\LabTrack.CSharp\src\LabTrack.Api\Extensions\CorsExtensions.cs
- backend\LabTrack.CSharp\src\LabTrack.Api\Extensions\JsonExtensions.cs
- backend\LabTrack.CSharp\src\LabTrack.Api\Extensions\ServiceCollectionExtensions.cs
- backend\LabTrack.CSharp\src\LabTrack.Api\Extensions\SwaggerExtensions.cs
- backend\LabTrack.CSharp\src\LabTrack.Api\Models\AiChatModels.cs
- backend\LabTrack.CSharp\src\LabTrack.Api\Models\AnalyticsModels.cs
- backend\LabTrack.CSharp\src\LabTrack.Api\Models\AssetModels.cs
- backend\LabTrack.CSharp\src\LabTrack.Api\Models\AuditModels.cs
- backend\LabTrack.CSharp\src\LabTrack.Api\Models\CommunicationModels.cs
- backend\LabTrack.CSharp\src\LabTrack.Api\Models\FinancialModels.cs
- backend\LabTrack.CSharp\src\LabTrack.Api\Models\LaboratoryModels.cs
- backend\LabTrack.CSharp\src\LabTrack.Api\Models\MaintenanceModels.cs

## Frontend Changes

- Total TS/TSX files: 71
- Modified since v2: 15
- New files since v2: 2

### Top frontend modifications

- frontend\src\api\apiClient.ts
- frontend\src\api\client.ts
- frontend\src\assets\styles\fonts.css
- frontend\src\components\admin\AiAssistantView.tsx
- frontend\src\components\admin\CampusesLabsView.tsx
- frontend\src\components\admin\QrGeneratorModal.tsx
- frontend\src\components\common\GlobalAiChatbot.tsx
- frontend\src\components\instructor\AiAssistantView.tsx
- frontend\src\components\portal\HeaderNotificationBell.tsx
- frontend\src\config\env.ts
- frontend\src\hooks\useRealtime.ts
- frontend\src\lib\api-client.ts
- frontend\src\lib\axios.ts
- frontend\src\lib\data-adapters.ts
- frontend\src\lib\signalr.ts

## New files in v3

### Backend additions

- (none)

### Frontend additions

- frontend\src\api\services.ts
- frontend\src\components\common\AiRichMessageRenderer.tsx

## Infrastructure cleanup

- Removed stray Compile Include directives from csproj files (CS0101 fix)
- Removed bak and cleanup text artifacts from working tree
- Updated .gitignore to prevent re-commit

## Controllers in this build

- AiAssistant
- Analytics
- Asset
- Audit
- Auth
- ChainOfCustody
- Communication
- Financial
- IdempotencyRecords
- InstructorCommunication
- Laboratories
- Maintenance
- MaintenanceRecord
- MaintenanceRecords
- Network
- NetworkIncident
- NetworkInfo
- Notification
- PcUsage
- ProblemReport
- QrAdmin
- Qr
- QrSession
- RepairTicket
- Replacement
- ReplacementRecord
- Reservation
- Users
- Workstations

---

Auto-generated on 2026-11-19 03:13:50
