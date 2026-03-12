# Branch Cleanup Analysis - March 12, 2026

## Summary Statistics (from `git branch -r` — 61 total)
- **Total Branches**: 61
- **Completed (merged to main)**: 18
- **In Testing/Staging (not yet in main)**: 9
- **Ready for Merge (in dev only)**: 1
- **In Development (not merged anywhere)**: 21
- **Protected / Infrastructure**: 5 (main, prod, dev, Testing/Staging, origin)
- **Prod/Backup branches**: 7

> _Status determined by `git branch -r --merged` against `origin/main`, `origin/Testing/Staging`, and `origin/dev` as of 2026-03-12_

---

## ✅ COMPLETED — Merged to `main` (18 branches)

| Branch | Last Updated | Notes |
|--------|--------------|-------|
| clinician_additional_logins | 2026-02-20 | Safe to delete |
| cwa-notification-email | 2026-01-24 | Safe to delete |
| cwa-password-redirect-url | 2026-01-24 | Safe to delete |
| cwa-record-pii | 2026-01-24 | Safe to delete |
| cwa_notfication_email_resend | 2026-01-24 | Safe to delete |
| feature/cwa-record-consult | 2026-01-12 | Safe to delete |
| memory-lin | 2026-02-05 | Safe to delete |
| pwa-back-end | 2026-02-05 | Safe to delete |
| pwa-multiple-summary-generation | 2026-01-24 | Safe to delete |
| pwa-password-reset | 2026-01-24 | Safe to delete |
| main_backup_2_11_2026 | 2026-02-08 | Backup — archive/delete |
| main_include_replit_into_pwa | 2026-02-12 | Safe to delete |
| Prod-oncology | 2026-01-19 | Safe to delete |
| prod_11th | 2026-02-11 | Safe to delete |
| prod_backup_jan17 | 2026-01-14 | Backup — archive/delete |
| prod_n | 2026-02-05 | Safe to delete |
| prodBackupJan14 | 2026-01-12 | Backup — archive/delete |
| prodo4mini | 2026-01-19 | Safe to delete |

---

## 🟡 IN TESTING — In `Testing/Staging`, NOT yet in `main` (9 branches)

| Branch | Last Updated | Author | Notes |
|--------|--------------|--------|-------|
| Feat/authrequirederror | 2026-03-12 | ZHANG MUZI | Awaiting merge to main |
| Feat/summaryDBfix | 2026-03-09 | Tanmay Nargas | Awaiting merge to main |
| Feat/PHIredactionfix | 2026-02-28 | biswa | Awaiting merge to main |
| Feat/PWAmodel_fallbacks | 2026-02-28 | biswa | Awaiting merge to main |
| Feat/PWAmodel_fallbacks_updated | 2026-02-28 | biswa | Awaiting merge to main |
| Feat/health_profile_extraction | 2026-02-28 | biswa | Awaiting merge to main |
| Feat/userleakagefix | 2026-02-28 | biswa | Awaiting merge to main |
| Fixed_consult_batch_summary_generation_using_lemur | 2026-02-28 | biswa | Awaiting merge to main |
| DB_Merge | 2026-02-24 | darblueone-tech | Awaiting merge to main |

---

## 🔵 READY FOR MERGE — In `dev`, NOT in `Testing/Staging` (1 branch)

| Branch | Last Updated | Author | Notes |
|--------|--------------|--------|-------|
| Patient_summary_CWA | 2026-01-15 | NitikaNahata | Needs promotion to Testing/Staging |

---

## 🟠 IN DEVELOPMENT — Not merged anywhere (21 branches)

| Branch | Last Updated | Author | Notes |
|--------|--------------|--------|-------|
| cwa_create_appointment | 2026-03-12 | SQM | Active dev |
| Feat/CWAdesktopconsult | 2026-03-12 | ZHANG MUZI | Active dev |
| zmz/local-setup | 2026-03-11 | Rothbart | Active dev |
| Feat/CWAPWAmultitenancy | 2026-03-09 | Tanmay Nargas | Active dev |
| Feat/soundcapturefix | 2026-03-04 | Tanmay Nargas | Active dev |
| cwa-changes-for-pwa-new-ui | 2026-03-02 | Ardacandra | Active dev |
| merge/feat-tanmay-into-testing-20260224 | 2026-02-24 | Satyam | Merge branch — check if still needed |
| Feat/tanmay | 2026-02-24 | Satyam | Active dev |
| CWA_Authorization_Error | 2026-02-21 | carrotong | Active dev |
| cwa-medical-model | 2026-02-18 | BISWA192111 | Active dev |
| multi-lingual_ASR_models | 2026-02-15 | BISWA192111 | Active dev |
| copilot/update-user-profile-page | 2026-02-11 | copilot-swe-agent[bot] | Bot branch — check if needed |
| pwa-back-end-newUI | 2026-02-09 | Ardacandra | Check with Ardacandra |
| pwa-front-end | 2026-02-08 | Ardacandra | Check with Ardacandra |
| cwa-record-consult | 2026-02-08 | BISWA192111 | Check with Biswajit |
| cwa-appointment-UI | 2026-02-06 | harshalmad | Check with harshalmad |
| cwa-record | 2026-01-24 | unm63 | Check with Ujwal |
| prod-dev-merge-branch | 2026-01-18 | NitikaNahata | Check with Nitika |
| prod-dev-merge-branch_2 | 2026-01-18 | NitikaNahata | Check with Nitika |
| feature/memory-mvp/haoxuan | 2025-11-20 | coderinmac | 🔴 ~113 days old — DELETE |
| feature/memory-mvp/akshay | 2025-10-18 | akshayyy | 🔴 ~146 days old — DELETE |
| memory-mvp-2025-10-13 | 2025-10-16 | evolve2learn | 🔴 ~148 days old — DELETE |

---

## 🟡 PROTECTED / INFRASTRUCTURE BRANCHES (keep always)

| Branch | Last Updated | Purpose |
|--------|--------------|---------|
| main | 2026-02-22 | Production source of truth |
| Testing/Staging | 2026-03-12 | Staging environment |
| dev | 2026-01-15 | Integration branch |
| prod | 2026-02-06 | Live production |
| origin (pointer) | 2026-02-22 | Default branch pointer |

---

## 🗂️ PROD / BACKUP BRANCHES (7 branches — not merged to main)

| Branch | Last Updated | Author | Notes |
|--------|--------------|--------|-------|
| prod_Ujwal | 2026-02-22 | unm63 | Active prod branch |
| prod_Ujwal_2 | 2026-02-01 | unm63 | Check with Ujwal |
| prod_onco | 2026-01-29 | NitikaNahata | Check with Nitika |
| prod_demo_wed | 2026-02-10 | NitikaNahata | Demo branch |
| prod_dept | 2026-02-10 | NitikaNahata | Active prod branch |
| dev_backup | 2026-01-15 | NitikaNahata | Backup — archive/delete? |
| carrotong-patch-1 | 2026-03-13 | carrotong | Active — NOT merged |

---

## 🔴 STALE BRANCHES (90+ Days — before Jan 12, 2026)

| Branch | Last Updated | Author | Merged? | Age | Recommendation |
|--------|--------------|--------|---------|-----|----------------|
| feature/memory-mvp/haoxuan | 2025-11-20 | coderinmac | ❌ | ~113 days | **DELETE** |
| feature/memory-mvp/akshay | 2025-10-18 | akshayyy | ❌ | ~146 days | **DELETE** |
| memory-mvp-2025-10-13 | 2025-10-16 | evolve2learn | ❌ | ~148 days | **DELETE** |

---

## 📊 ACTION ITEMS BY DEVELOPER

### **Biswa/Biswajit (BISWA192111/biswa)**
**Active — keep:**
- cwa-medical-model (Feb 18) - IN DEV
- multi-lingual_ASR_models (Feb 15) - IN DEV
- cwa-record-consult (Feb 8) - IN DEV, check if still needed

**In Testing/Staging — awaiting merge to main:**
- Feat/PHIredactionfix, Feat/PWAmodel_fallbacks, Feat/PWAmodel_fallbacks_updated, Feat/health_profile_extraction, Feat/userleakagefix, Fixed_consult_batch_summary_generation_using_lemur

### **ZHANG MUZI**
**Active — keep:**
- Feat/CWAdesktopconsult (Mar 12) - IN DEV

**In Testing/Staging — awaiting merge to main:**
- Feat/authrequirederror

### **Tanmay Nargas**
**Active — keep:**
- Feat/CWAPWAmultitenancy (Mar 9) - IN DEV
- Feat/soundcapturefix (Mar 4) - IN DEV
- Feat/tanmay (Feb 24) - IN DEV
- merge/feat-tanmay-into-testing-20260224 (Feb 24) — check if still needed

**In Testing/Staging — awaiting merge to main:**
- Feat/summaryDBfix

### **Ujwal (unm63)**
**Active — keep:**
- prod_Ujwal (Feb 22) - active prod

**To review:**
- prod_Ujwal_2 (Feb 1) - check if needed
- cwa-record (Jan 24) - IN DEV, check if needed

**Safe to delete (merged to main):**
- main_backup_2_11_2026, memory-lin, pwa-back-end, Prod-oncology, prodo4mini, prod_backup_jan17, prodBackupJan14

### **NitikaNahata**
**Active — keep:**
- prod_dept (Feb 10), prod_demo_wed (Feb 10) - active prod

**To review:**
- prod_onco (Jan 29), prod-dev-merge-branch (Jan 18), prod-dev-merge-branch_2 (Jan 18)
- Patient_summary_CWA (Jan 15) - in dev, READY to push to Testing/Staging
- dev_backup (Jan 15) - backup

**Safe to delete (merged to main):**
- clinician_additional_logins, prod_11th, prod_n, cwa-notification-email, cwa-password-redirect-url, feature/cwa-record-consult

### **Ardacandra**
**Active — keep:**
- cwa-changes-for-pwa-new-ui (Mar 2) - IN DEV

**To review:**
- pwa-back-end-newUI (Feb 9) - IN DEV
- pwa-front-end (Feb 8) - IN DEV

### **SQM**
- cwa_create_appointment (Mar 12) - IN DEV, active

### **Rothbart (zmz)**
- zmz/local-setup (Mar 11) - IN DEV, active

### **Satyam**
**To review:**
- merge/feat-tanmay-into-testing-20260224 (Feb 24) - check if still needed

**Safe to delete (merged to main):**
- cwa_notfication_email_resend, pwa-multiple-summary-generation

### **Others**
- **carrotong** — CWA_Authorization_Error (Feb 21): IN DEV; carrotong-patch-1 (Mar 13): active
- **harshalmad** — cwa-appointment-UI (Feb 6): IN DEV; pwa-password-reset ✅ merged
- **thaf-exe** — main_include_replit_into_pwa ✅ merged
- **darblueone-tech** — DB_Merge: in Testing/Staging, awaiting merge to main
- **copilot-swe-agent[bot]** — copilot/update-user-profile-page (Feb 11): check if needed
- **coderinmac** — feature/memory-mvp/haoxuan 🔴 DELETE (113 days old)
- **akshayyy** — feature/memory-mvp/akshay 🔴 DELETE (146 days old)
- **evolve2learn** — memory-mvp-2025-10-13 🔴 DELETE (148 days old)

---

## 🎯 IMMEDIATE ACTIONS

### **Safe to Delete NOW (18 branches — Already Merged to main):**
```bash
git push origin --delete clinician_additional_logins
git push origin --delete cwa-notification-email
git push origin --delete cwa-password-redirect-url
git push origin --delete cwa-record-pii
git push origin --delete cwa_notfication_email_resend
git push origin --delete feature/cwa-record-consult
git push origin --delete memory-lin
git push origin --delete pwa-back-end
git push origin --delete pwa-multiple-summary-generation
git push origin --delete pwa-password-reset
git push origin --delete main_backup_2_11_2026
git push origin --delete main_include_replit_into_pwa
git push origin --delete Prod-oncology
git push origin --delete prod_11th
git push origin --delete prod_backup_jan17
git push origin --delete prod_n
git push origin --delete prodBackupJan14
git push origin --delete prodo4mini
```

### **Stale — Confirm with Dev then Delete (3 branches):**
```bash
git push origin --delete feature/memory-mvp/haoxuan
git push origin --delete feature/memory-mvp/akshay
git push origin --delete memory-mvp-2025-10-13
```

### **Next Step — Merge Testing/Staging → main (9 branches in queue):**
- Feat/authrequirederror, Feat/summaryDBfix, Feat/PHIredactionfix
- Feat/PWAmodel_fallbacks, Feat/PWAmodel_fallbacks_updated
- Feat/health_profile_extraction, Feat/userleakagefix
- Fixed_consult_batch_summary_generation_using_lemur, DB_Merge

### **Promote to Testing/Staging (1 branch ready in dev):**
- Patient_summary_CWA (NitikaNahata)

### **Need Developer Input (check still needed):**
- cwa-record-consult, pwa-back-end-newUI, pwa-front-end (Ardacandra/Biswajit)
- cwa-appointment-UI (harshalmad)
- prod_Ujwal_2, cwa-record (Ujwal)
- prod_onco, prod-dev-merge-branch, prod-dev-merge-branch_2, dev_backup (Nitika)
- CWA_Authorization_Error (carrotong)
- copilot/update-user-profile-page (bot)
- merge/feat-tanmay-into-testing-20260224 (Satyam)

---
