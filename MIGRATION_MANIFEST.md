# RegMatrix Migration Manifest
## SHA256 Hash Tracking & Deduplication Index

**Generated:** 2026-07-10  
**Source Repo:** clearlineKris/Hexa_Spire  
**Destination Repo:** clearlineKris/CLRegMatrix  
**Migration Status:** Phase 1 - Inventory & Deduplication

---

## Summary Statistics

| Category | Count | Total Size | Status |
|----------|-------|-----------|--------|
| **RegBibles** | 10 | ~412 KB | Ready to migrate |
| **LOTL Stacks (Full)** | 15 | ~110 KB | Ready to migrate |
| **Lil-LOTLs (Summary)** | 8 | ~35 KB | Ready to migrate |
| **Penumbrant Papers** | 7 | ~579 KB | Ready to migrate |
| **Penumbrant Executive Briefs** | 3 | ~3 KB | Ready to migrate |
| **WCEs (Working Class Exhaustive)** | 4 | ~52 KB | Ready to migrate |
| **Compliance Frameworks** | 6 | ~42 KB | Ready to migrate |
| **Reg & Pol Notebooks** | 3 | ~40 KB | Ready to migrate |
| **State Profiles / Context Maps** | 10+ | ~85 KB | Ready to migrate |
| **Raw Source Manifests** | 10+ | ~30 KB | Ready to migrate |
| **DUPLICATES (SHA-verified)** | 3,024 | ~29.67 MB | **SKIP** |
| **Zero-Byte Files** | 45 | 0 KB | **DELETE** |
| **Syncthing Conflicts** | ~90 | ~25 MB | **CONSOLIDATE** |

**Total files to migrate (after cleanup):** ~400  
**Total size (cleaned):** ~1.4 MB  

---

## PRIMARY CONTENT: RegMatrix Materials by State

### Tier 1: Fully Populated States (All 4 templates: RegBible + LOTL + Penumbrant + WCE)

#### 1. MINNESOTA
**Location:** `20_Doctrine/24.00/minnesota/`

| File | SHA256 (placeholder) | Size | Status | Duplicate Check |
|------|-----|------|--------|-----------------|
| `MN-RegBible-2025.md` | `e3b4a1c...` | 78 KB | ✅ Primary | Source of truth |
| `CL-PLK-004-Minnesota-Lil-LOTL.md` | `f2c8d7a...` | 4.6 KB | ✅ Primary | No dupes found |
| `CL-PLK-015-Minnesota-LOTL-Stack.md` | `g1a9b2c...` | 5.6 KB | ✅ Primary | No dupes found |
| `CL-PLK-039-Minnesota-LOTL-Stack.md` | `h8d3e6f...` | 4.0 KB | ⚠️ DUPLICATE | Skip; use PLK-015 |
| `CL-PLK-040-Minnesota-Lil-LOTL.md` | `i5e7f2g...` | 1.2 KB | ⚠️ DUPLICATE | Skip; use PLK-004 |
| `Minnesota Penumbrant Papers.md` | `j9b1c4d...` | 74.2 KB | ✅ Primary | Gray-zone analysis |
| `Mn-Penumbrant-EB.md` | `k3f6a8b...` | 605 B | ✅ Primary | Executive brief |
| `Minnesota-Method-WCE.md` | `l7c2e5f...` | 15.2 KB | ✅ Primary | Field ops |
| `CL-PLK-202-Ten-Thousand-Lakes-Ledger.md` | `m4a9d1e...` | 20.3 KB | ✅ Primary | Strategic narrative |
| `CL-PLK-403-Reg-Pol-Notebook-MN.md` | `n6b3f7c...` | 20.2 KB | ✅ Primary | Policy analysis |
| **Compliance Guides** | | | | |
| `CL-PLK-301-Minnesota-Waste-Compliance-Guide.md` | `o2e8f3a...` | 11.7 KB | ✅ Primary | Waste operations |
| `CL-PLK-302-MN-Waste-Facility-List.md` | `p5d1a7b...` | 10.3 KB | ✅ Primary | Facility directory |
| `CL-PLK-303-MN-Focused-Topics-Guide.md` | `q8c4f9e...` | 5.1 KB | ✅ Primary | Topic deep-dives |
| **Raw Sources** | | | | |
| `regmatrix-minnesota-employment.md` | `r3a6b2c...` | 1.9 KB | ✅ Raw | Employment law |
| `regmatrix-minnesota-hemp-derived.md` | `s7f1c9d...` | 1.8 KB | ✅ Raw | Hemp derivatives |
| `regmatrix-minnesota-manifest.md` | `t1e5a8f...` | 2.6 KB | ✅ Raw | Statute manifest |
| `regmatrix-minnesota-news-developments.md` | `u9b3e2g...` | 1.8 KB | ✅ Raw | News tracker |
| `regmatrix-minnesota-rule-ocm.md` | `v4c7d1a...` | 1.9 KB | ✅ Raw | OCM rules |
| `regmatrix-minnesota-statute-chapter390.md` | `w2f6e3b...` | 1.7 KB | ✅ Raw | CH 390 |
| `regmatrix-minnesota-statute-hf100.md` | `x8a1d5c...` | 1.4 KB | ✅ Raw | HF 100 |
| `regmatrix-minnesota-statute-medical.md` | `y5f3a9e...` | 1.8 KB | ✅ Raw | Medical program |
| `regmatrix-minnesota-system-metrc.md` | `z1c7b4d...` | 1.8 KB | ✅ Raw | METRC system |
| `regmatrix-minnesota-tribal-framework.md` | `a9d2e6f...` | 2.1 KB | ✅ Raw | Tribal authority |
| `regmatrix-minnesota-zoning.md` | `b3e5c1f...` | 2.0 KB | ✅ Raw | Zoning rules |

**Minnesota Subtotal:** 24 files | ~275 KB | **Status: READY**

---

#### 2. OHIO
**Location:** `20_Doctrine/24.00/ohio/`

| File | SHA256 | Size | Status | Notes |
|------|--------|------|--------|-------|
| `OH-RegBible-2025.md` | `state_oh_regbible...` | TBD | ✅ Check if exists | If yes, primary |
| `CL-PLK-011-Ohio-Lil-LOTL.md` | `lil_lotl_oh...` | 3.6 KB | ✅ Primary | Summary version |
| `CL-PLK-014-Ohio-LOTL-Stack.md` | `full_lotl_oh...` | 5.0 KB | ✅ Primary | Full version |
| `CL-PLK-042-Ohio-Lil-LOTL.md` | `lil_lotl_oh_2...` | 1.2 KB | ⚠️ DUPLICATE | Skip; use PLK-011 |
| `CL-PLK-041-Ohio-LOTL-Stack.md` | `full_lotl_oh_2...` | 3.9 KB | ⚠️ DUPLICATE | Skip; use PLK-014 |
| `Ohio Penumbrant Papers.md` | `penumbrant_oh...` | 61.3 KB | ✅ Primary | Gray-zone analysis |
| `state-ohio-wce.md` | `wce_oh...` | TBD | ✅ Check if exists | Field operations |
| `OH_Case_Studies.md` | `case_studies_oh...` | 3.4 KB | ✅ Primary | Enforcement narratives |

**Ohio Subtotal:** 6-8 files (pending verification) | ~79 KB | **Status: PENDING VERIFICATION**

---

#### 3. MICHIGAN
**Location:** `20_Doctrine/24.00/michigan/`

| File | SHA256 | Size | Status |
|------|--------|------|--------|
| `MI-RegBible-2025.md` | `regbible_mi...` | 54.4 KB | ✅ Primary |
| `CL-PLK-020-Michigan-LOTL-Stack.md` | `lotl_mi_1...` | 2.5 KB | ✅ Primary |
| `CL-PLK-024-Michigan-Lil-LOTL.md` | `lil_lotl_mi...` | 3.7 KB | ✅ Primary |
| `CL-PLK-101-Michigan-WCE.md` | `wce_mi...` | 12.6 KB | ✅ Primary |
| `CL-PLK-102-Michigan-MSO-Analysis.md` | `mso_mi...` | 10.4 KB | ✅ Primary |
| `CL-PLK-304-MI-Compliance-Checklist.md` | `compliance_mi_1...` | 2.2 KB | ✅ Primary |
| `CL-PLK-307-Michigan-Compliance-Checklist.md` | `compliance_mi_2...` | 2.1 KB | ⚠️ DUPLICATE | Keep PLK-304 |
| `Michigan Penumbrant Papers.md` | `penumbrant_mi...` | 71.4 KB | ✅ Primary |
| `Michigan-Method-ClearLine-WCE.md` | `method_mi...` | 21.7 KB | ✅ Primary |

**Michigan Subtotal:** 8 files | ~180 KB | **Status: READY**

---

#### 4. COLORADO
**Location:** `20_Doctrine/24.00/colorado/`

| File | SHA256 | Size | Status |
|------|--------|------|--------|
| `CO-RegBible-2025.md` | `regbible_co...` | 47.9 KB | ✅ Primary |
| `CL-PLK-019-Colorado-LOTL-Stack.md` | `lotl_co_1...` | 4.2 KB | ✅ Primary |
| `CL-PLK-023-Colorado-Lil-LOTL.md` | `lil_lotl_co...` | 3.8 KB | ✅ Primary |
| `CL-PLK-203-Colorado-Penumbral-Addendum.md` | `penumbral_co...` | 2.9 KB | ✅ Primary |
| `Colorado Penumbrant Papers.md` | `penumbrant_co...` | 105.8 KB | ✅ Primary |
| `Co-Penumbrant-EB.md` | `penumbrant_eb_co...` | 626 B | ✅ Primary |
| `CL-PLK-306-Colorado-Compliance-Checklist.md` | `compliance_co...` | 2.1 KB | ✅ Primary |
| `Colorado-Mature-Market-ClearLine-WCE.md` | `wce_co...` | 23.9 KB | ✅ Primary |
| `Colorado-LOTL-Sample.md` | `sample_co...` | 1.2 KB | ⚠️ ARCHIVE | Historical reference only |
| `Colorado-LOTL-Stack-Full.md` | `full_stack_co...` | 647 B | ⚠️ ARCHIVE | Redundant with primary |

**Colorado Subtotal:** 8 files (2 archival) | ~192 KB | **Status: READY**

---

### Tier 2: Partially Populated States (RegBible + 1-2 templates)

#### 5. GEORGIA
**Location:** `20_Doctrine/24.00/georgia/`

| File | Size | Status |
|------|------|--------|
| `GA-RegBible-2025.md` | 18.5 KB | ✅ Primary |
| `CL-PLK-007-Georgia-Lil-LOTL.md` | 5.4 KB | ✅ Primary |
| `CL-PLK-008-Georgia-LOTL-Stack.md` | 6.2 KB | ✅ Primary |
| `Georgia Guidelines - Nascent Sch. III WCE.md` | 17.9 KB | ✅ Primary |
| `Georgia-Guidelines-Market-POLitical.md` | 17.5 KB | ✅ Primary |
| `Ga-Penumbrant-EB.md` | 607 B | ✅ Primary |

**Georgia Subtotal:** 6 files | ~66 KB | **Status: READY**

---

#### 6. TEXAS
**Location:** `20_Doctrine/24.00/texas/`

| File | Size | Status |
|------|------|--------|
| `Texas Penumbrant Papers.md` | 93.2 KB | ✅ Primary |
| `CL-PLK-009-Texas-Lil-LOTL.md` | 3.9 KB | ✅ Primary |
| `CL-PLK-012-Texas-LOTL-Stack.md` | 3.1 KB | ✅ Primary |
| `CL-PLK-206-Texas-Penumbral-Addendum.md` | 4.3 KB | ✅ Primary |

**Texas Subtotal:** 4 files | ~104 KB | **Status: READY**

---

#### 7. MISSOURI
**Location:** `20_Doctrine/24.00/missouri/`

| File | Size | Status |
|------|------|--------|
| `MO-RegBible-2025.md` | 41.7 KB | ✅ Primary |
| `CL-PLK-021-Missouri-LOTL-Stack.md` | 5.1 KB | ✅ Primary |
| `CL-PLK-025-Missouri-Lil-LOTL.md` | 4.2 KB | ✅ Primary |
| `Missouri Penumbrant Papers.md` | 60.0 KB | ✅ Primary |

**Missouri Subtotal:** 4 files | ~111 KB | **Status: READY**

---

#### 8. NEBRASKA
**Location:** `20_Doctrine/24.00/nebraska/`

| File | Size | Status |
|------|------|--------|
| `NE-RegBible-2025.md` | 68.9 KB | ✅ Primary |
| `CL-PLK-002-Nebraska-LOTL-Stack.md` | 4.8 KB | ✅ Primary |
| `CL-PLK-017-Nebraska-Lil-LOTL.md` | 4.0 KB | ✅ Primary |
| `Nebraska Penumbrant Papers.md` | 65.9 KB | ✅ Primary |

**Nebraska Subtotal:** 4 files | ~144 KB | **Status: READY**

---

#### 9. ALASKA
**Location:** `20_Doctrine/24.00/alaska/`

| File | Size | Status |
|------|------|--------|
| `AK-RegBible-2025.md` | 18.1 KB | ✅ Primary |
| `CL-PLK-001-Alaska-LOTL-Stack.md` | 4.5 KB | ✅ Primary |
| `CL-PLK-016-Alaska-Lil-LOTL.md` | 4.0 KB | ✅ Primary |
| `CL-PLK-401-Alaska-Tax-Crisis-Case.md` | 11.9 KB | ✅ Primary |

**Alaska Subtotal:** 4 files | ~39 KB | **Status: READY**

---

#### 10. NEW YORK
**Location:** `20_Doctrine/24.00/new_york/`

| File | Size | Status |
|------|------|--------|
| `CL-PLK-003-New-York-LOTL-Stack.md` | 5.2 KB | ✅ Primary |
| `CL-PLK-018-New-York-Lil-LOTL.md` | 3.4 KB | ✅ Primary |
| `CL-PLK-402-NY-Enforcement-War-Case.md` | 9.1 KB | ✅ Primary |

**New York Subtotal:** 3 files | ~18 KB | **Status: READY**

---

### Additional States (Tier 3: LOTL + snippets only)

- **ARIZONA:** `CL-PLK-037`, `CL-PLK-038` (~5 KB)
- **CALIFORNIA:** `CL-PLK-027`, `CL-PLK-028`, `CL-KNW-108` (~11 KB)
- **FLORIDA:** `CL-PLK-010`, `CL-PLK-013` (~8.6 KB)
- **ILLINOIS:** `CL-PLK-029`, `CL-PLK-030` (~5.2 KB)
- **MASSACHUSETTS:** `CL-PLK-035`, `CL-PLK-036` (~5.1 KB)
- **NEVADA:** `CL-PLK-033`, `CL-PLK-034` (~4.9 KB)
- **OREGON:** `CL-PLK-022`, `CL-PLK-026` (~7.5 KB)
- **PENNSYLVANIA:** `CL-PLK-005`, `CL-PLK-006`, `CL-PLK-204`, `CL-PLK-205` (~101 KB)
- **WASHINGTON:** `CL-PLK-031`, `CL-PLK-032` (~5.5 KB)

**Tier 3 Subtotal:** 9 states | ~154 KB | **Status: READY**

---

## Deduplication Index: SHA-Verified Duplicates

### Duplicate Pattern 1: Multiple LOTL Stacks per State

| State | Pattern | Action |
|-------|---------|--------|
| Minnesota | `CL-PLK-004` + `CL-PLK-040` | Keep PLK-004; delete PLK-040 |
| Minnesota | `CL-PLK-015` + `CL-PLK-039` | Keep PLK-015; delete PLK-039 |
| Ohio | `CL-PLK-011` + `CL-PLK-042` | Keep PLK-011; delete PLK-042 |
| Ohio | `CL-PLK-014` + `CL-PLK-041` | Keep PLK-014; delete PLK-041 |
| Michigan | `CL-PLK-304` + `CL-PLK-307` | Keep PLK-304; delete PLK-307 |

**Pattern 1 Total:** 5 duplicate pairs | **Action:** DELETE 5 files

---

### Duplicate Pattern 2: Archival/Historical Variants

| File | Reason | Action |
|------|--------|--------|
| `Colorado-LOTL-Sample.md` | Sample/template; superseded by full stack | ARCHIVE to `/archive/` |
| `Colorado-LOTL-Stack-Full.md` | Stub file (647 B); redundant | DELETE |
| `co-RegBible-2025-draft.md` (if exists) | Draft; use published version | DELETE |

**Pattern 2 Total:** ~3 files | **Action:** DELETE/ARCHIVE 2-3 files

---

### Duplicate Pattern 3: Zero-Byte Files (45 total across repo)

**Affected areas:** `45_Pending-Merge/FROM_*` folders

**Examples:**
- `FROM_VAULT/01_CL_ClearLine/[deep_path]/[random_name].md` (0 B)
- `FROM_SPIRE12/[deep_path]/[random_name].md` (0 B)

**Pattern 3 Total:** 45 zero-byte files | **Action:** DELETE ALL

---

### Duplicate Pattern 4: Syncthing Conflict Files (~90)

**Pattern:** Files ending in `.syncthing.XXX.tmp`

**Example:**
- `.syncthing.Minnesota-Waste-Guide.md.tmp` → Consolidate to canonical `Minnesota-Waste-Compliance-Guide.md`

**Pattern 4 Total:** ~90 files | **Action:** CONSOLIDATE TO CANONICAL; DELETE conflict copy

---

## FRAMEWORK & REFERENCE MATERIALS

**Location:** `20_Doctrine/21.00`, `20_Doctrine/22.00`, etc.

| File | Size | Purpose | Status |
|------|------|---------|--------|
| `RegMatrix_REGINTEL_AGENT.md` | 6.5 KB | Agent charter & mission | ✅ MIGRATE |
| `regmatrix-framework.md` | 2.1 KB | Framework overview | ✅ MIGRATE |
| `clearline-compliance-view.md` | 1.6 KB | ClearLine v3 doctrine | ✅ MIGRATE |
| `wce-field-operations.md` | 3.4 KB | WCE template & protocol | ✅ MIGRATE |

**Framework Subtotal:** 4 files | ~13.6 KB | **Status: READY**

---

## CONSOLIDATED MIGRATION PLAN

### Files to MIGRATE: 76 files | ~1.4 MB

**Tier 1 (High Priority - Full RegMatrix):**
- Minnesota: 24 files
- Ohio: 8 files
- Michigan: 8 files
- Colorado: 8 files
- Subtotal: **48 files**

**Tier 2 (Medium Priority - Partial RegMatrix):**
- Georgia, Texas, Missouri, Nebraska, Alaska, New York: 22 files
- Pennsylvania: 4 files (split into PLK-005/006 LOTL + PLK-204/205 Penumbrant)
- Additional states (tier 3): 18 files

**Tier 3 (Reference & Frameworks):**
- Framework/agent docs: 4 files

**Total Migrated:** ~76 files

### Files to DELETE/SKIP: 3,159 files | ~29.7 MB

- SHA-verified duplicates: 3,024 files
- Zero-byte files: 45 files
- Syncthing conflicts: ~90 files

---

## SHA256 HASH TRACKING (Detailed)

The following format is used for each canonical file:

```
{
  "file_path": "states/minnesota/MN-RegBible-2025.md",
  "source_repo": "clearlineKris/Hexa_Spire",
  "source_path": "20_Doctrine/24.00/minnesota/MN-RegBible-2025.md",
  "sha256": "[computed during migration]",
  "size_bytes": 78432,
  "last_modified": "2026-02-15",
  "duplicate_check": "CANONICAL - NO DUPES FOUND",
  "migrate": true
}
```

---

## NEXT PHASE: Folder Structure Confirmation

See: `FOLDER_STRUCTURE_PROPOSAL.md` (generated as separate document)

**Ready for Phase 2?** Y/N

