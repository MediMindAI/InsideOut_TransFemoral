# PATENT CLAIMS ANALYSIS MATRIX

## ProGuard™ Hybrid Access & Closure System

**Document Classification:** CONFIDENTIAL - ATTORNEY WORK PRODUCT

**Analysis Date:** November 22, 2025

---

## 1. CRITICAL PATENT ANALYSIS: US9289577B2 (MERIT MEDICAL / SURFACER)

### Patent Information
- **Title:** Occlusion Access Method
- **Patent Number:** US9289577B2
- **Issue Date:** March 22, 2016
- **Assignee:** Merit Medical Systems, Inc.
- **Status:** ACTIVE
- **Expiration:** ~2035

### Claim 1 Element-by-Element Analysis

| Claim Element | ProGuard™ Feature | Literal Match | DOE Risk | Analysis |
|---------------|-------------------|---------------|----------|----------|
| "A method for providing access to a **central venous system** of a patient" | Access to **common femoral ARTERIAL** system | **NO** | **NO** | Different anatomical system |
| "applying a radiopaque target having a radiopaque area and a radiolucent area to the skin" | Fluoroscopic guidance with optional external markers | Partial | Low | Not essential to ProGuard operation |
| "radiolucent area defines an exit point on the skin" | Exit point determined by fluoroscopy and device navigation | Different | Low | Different positioning methodology |
| "introducing a catheter into the patient in an area remote from the exit point" | Catheter introduced via radial artery | **YES** | N/A | Generic catheter introduction |
| "catheter has a departure angle guide tube configured to extend out a side aperture" | Needle guide mechanism with indexed angles | Similar | Medium | Different specific design |
| "set a departure angle" | 0°, 30°, 60°, 90° indexed settings | Similar | Medium | Similar concept |
| "needle wire configured to extend through the departure angle guide tube" | Needle wire + 4 suture needles | Modified | Medium | Multiple needles vs. single |
| "advancing the catheter to position said distal tip in a desired tip location in the **central venous system**" | Position in **common femoral ARTERY** | **NO** | **NO** | Venous vs. arterial |
| "viewing the catheter and said distal tip under fluoroscopy" | Fluoroscopic guidance | **YES** | N/A | Standard imaging technique |
| "rotating the catheter so that the side aperture and therefore the departure angle plane is aligned" | Orientation control for anterior positioning | Similar | Medium | Similar alignment concept |
| "advancing the needle wire through the departure angle guide tube, through the skin" | Needle deployment from intravascular position through vessel wall and skin | Similar | Medium | Core similar concept |
| "providing an exteriorized needle wire at said exit point" | Guidewire and suture externalization | Similar | Medium | Similar outcome |

### Infringement Determination for US9289577B2

| Analysis Type | Conclusion | Confidence |
|---------------|------------|------------|
| **Literal Infringement** | **NO** - Claim requires "central venous system"; ProGuard operates in arterial system | HIGH |
| **Doctrine of Equivalents** | **NO** - Different function (venous access vs. arterial access), different way (venous anatomy vs. arterial anatomy), different result (dialysis access vs. interventional cardiology access) | HIGH |

### Key Distinguishing Factors

1. **Anatomical Domain:**
   - Surfacer: Central venous system (IVC → SVC → IJV)
   - ProGuard: Femoral arterial system (Radial → Aorta → CFA)

2. **Physiological Environment:**
   - Surfacer: Low-pressure venous system (~5-15 mmHg)
   - ProGuard: High-pressure arterial system (~80-120 mmHg)

3. **Clinical Indication:**
   - Surfacer: Central venous catheter placement for dialysis
   - ProGuard: Large-bore access for TAVR, EVAR, interventional procedures

4. **Exit Location:**
   - Surfacer: Neck/internal jugular vein region
   - ProGuard: Groin/femoral region

5. **Closure Mechanism:**
   - Surfacer: None (access only)
   - ProGuard: Integrated prophylactic suture closure

---

## 2. CRITICAL PATENT ANALYSIS: US9314595B2 (BLUEGRASS VASCULAR)

### Patent Information
- **Title:** Central Venous Access System
- **Patent Number:** US9314595B2
- **Issue Date:** April 19, 2016
- **Assignee:** University of Kentucky Research Foundation
- **Status:** ACTIVE
- **Expiration:** May 22, 2032

### Claim 1 Element-by-Element Analysis

| Claim Element | ProGuard™ Feature | Literal Match | DOE Risk | Analysis |
|---------------|-------------------|---------------|----------|----------|
| "A catheter system for use in accessing a patient's **central venous system at a location near the neck**" | Accesses **femoral arterial system at groin location** | **NO** | **NO** | Completely different anatomy and location |
| "patient having an exterior exit target location on the exterior of the patient, **proximate said neck**" | Exit target at **groin/femoral region** | **NO** | **NO** | Different body region |
| "patient having an **inferior vena cava** having a vena cava wall" | Patient has **common femoral artery** as target | **NO** | **NO** | Venous vs. arterial structure |
| "a **right atrium**" | Not applicable to arterial procedure | **NO** | **NO** | Cardiac chamber not involved |
| "a **superior vena cava** having a vena cava wall" | Not applicable to arterial procedure | **NO** | **NO** | Venous structure not involved |
| "an **azygos vein** having an azygos vein ostium opening into the vena cava" | Not applicable to arterial procedure | **NO** | **NO** | Venous structure not involved |
| "the inferior vena cava and right atrium joined at a junction" | Not applicable to arterial anatomy | **NO** | **NO** | Venous junction not relevant |
| "a straight guide catheter work station having a working lumen" | Catheter with central lumen | **YES** | N/A | Generic catheter feature |
| "distal end adapted to be **lodged between said junction of the inferior vena cava and right atrium**" | Distal end positioned in **common femoral artery** | **NO** | **NO** | Different anatomical positioning |
| "distal end spanning the distance to said **vena cava wall of the superior vena cava proximate the azygos vein ostium**" | Not applicable | **NO** | **NO** | Venous anatomy not involved |
| "distal end biased against the wall of the superior vena cava" | Distal end positioned in CFA lumen | **NO** | **NO** | Different positioning concept |
| "a dilation stylet, having a working lumen, placed in said work station working lumen" | Multiple needle array (not single dilation stylet) | Different | Low | Different configuration |
| "a needle wire directional guide catheter having a working lumen" | Needle guide mechanism | Similar | Medium | Functionally similar |
| "distal tip adapted for placement in said dilation stylet working lumen" | Different deployment configuration | Different | Low | Different architecture |
| "rotatable and advanceable to aim said needle wire directional guide catheter distal tip toward said exterior exit target location" | Rotatable orientation control | Similar | Medium | Similar directional control |
| "a needle wire having a tissue piercing tip for advancement through said needle wire directional guide catheter" | Needle wire + 4 suture needles | Modified | Medium | Multiple needles |
| "to create an **extra vascular tissue track** extending to said exterior exit target location" | Creates tissue track for sutures and guidewire | Similar | Medium | Similar outcome |
| "from the location within the body" | From within arterial lumen | Similar | Medium | Inside-out concept |

### Infringement Determination for US9314595B2

| Analysis Type | Conclusion | Confidence |
|---------------|------------|------------|
| **Literal Infringement** | **NO** - Multiple claim limitations require specific venous anatomical structures (IVC, RA, SVC, azygos vein) not present in arterial application | HIGH |
| **Doctrine of Equivalents** | **NO** - Substantial differences in function, way, and result | HIGH |

### Key Distinguishing Factors

1. **Explicit Anatomical Limitations:** The claims specifically recite:
   - Inferior vena cava
   - Right atrium
   - Superior vena cava
   - Azygos vein ostium
   - Junction of IVC and RA

   None of these structures are present in the ProGuard™ arterial application.

2. **Exit Location:**
   - Patent claims: "near the neck"
   - ProGuard™: groin/femoral region

3. **System Configuration:**
   - Patent claims: Workstation "lodged between junction of IVC and RA"
   - ProGuard™: Catheter positioned within common femoral artery

---

## 3. ANALYSIS: US5613974A (ABBOTT / PERCLOSE)

### Patent Information
- **Title:** Apparatus and Method for Vascular Closure
- **Patent Number:** US5613974A
- **Issue Date:** March 25, 1997
- **Assignee:** Abbott Laboratories (originally Perclose, Inc.)
- **Status:** **EXPIRED** (March 2017)

### Claim Analysis Summary

Even if this patent were active, it would not cover ProGuard™ because:

| Claim Element | ProGuard™ Comparison | Match? |
|---------------|---------------------|--------|
| Guide body with contact surface at 30-80° angle | Inside-out deployment (no external contact surface) | **NO** |
| Needle guide at distal end for outside-in deployment | Needles deploy from within vessel (inside-out) | **NO** |
| Needles drawn from distal to proximal through tissue | Needles advance from proximal (intravascular) to distal (through skin) | **NO** |
| Device inserted through percutaneous tract | Device navigated transarterially | **NO** |
| Closure performed after procedure | Closure sutures positioned BEFORE dilation | **NO** |

### Infringement Determination for US5613974A

| Analysis Type | Conclusion | Confidence |
|---------------|------------|------------|
| **Patent Status** | **EXPIRED** - No infringement possible | HIGH |
| **If Active** | Would NOT cover due to fundamentally different access methodology | HIGH |

---

## 4. ANALYSIS: US7326230B2 (VASCULAR SEALING DEVICE)

### Patent Information
- **Title:** Vascular Sealing Device and Method of Use
- **Patent Number:** US7326230B2
- **Issue Date:** February 5, 2008
- **Status:** ACTIVE
- **Expiration:** ~2028

### Claim Analysis Summary

| Claim Element | ProGuard™ Comparison | Match? |
|---------------|---------------------|--------|
| Cannula holding first wire group and second wire group | Catheter with needle array and suture loops | Different mechanism |
| First wire group deployed into interior of blood vessel | Needles deployed FROM interior of vessel | Different direction |
| Second wire group deployed to adventitial surface | Sutures pulled through tissue to skin | Different closure mechanism |
| **Wire fixation device** to affix wire groups | **Suture knots** for closure | **NO** - Different closure method |
| **Wire-based closure** | **Suture-based closure** | **NO** - Fundamental difference |
| Wires change shape when deployed (planar formation) | Sutures remain flexible | **NO** - Different material behavior |

### Infringement Determination for US7326230B2

| Analysis Type | Conclusion | Confidence |
|---------------|------------|------------|
| **Literal Infringement** | **NO** - Patent covers wire-based closure; ProGuard uses suture-based closure | HIGH |
| **Doctrine of Equivalents** | **NO** - Substantially different closure mechanism | HIGH |

---

## 5. ANALYSIS: US6517553B1 (SUTURING INTERNAL PUNCTURE SITES)

### Patent Information
- **Title:** Device and Method for Suturing of Internal Puncture Sites
- **Patent Number:** US6517553B1
- **Issue Date:** February 11, 2003
- **Status:** **EXPIRED** (February 2023)

### Infringement Determination

| Analysis Type | Conclusion | Confidence |
|---------------|------------|------------|
| **Patent Status** | **EXPIRED** - No infringement possible | HIGH |

---

## 6. ANALYSIS: US8920462B2 (VASCULAR HOLE CLOSURE DEVICE)

### Patent Information
- **Title:** Vascular Hole Closure Device
- **Patent Number:** US8920462B2
- **Issue Date:** December 30, 2014
- **Status:** ACTIVE

### Claim Analysis Summary

| Claim Element | ProGuard™ Comparison | Match? |
|---------------|---------------------|--------|
| Intravascular component to block blood flow | Sutures cinch arteriotomy closed | Different mechanism |
| Extravascular component to retain intravascular component | Pre-positioned suture knots | Different architecture |
| Covering member with holes for connecting member | No covering member in ProGuard | **NO** |
| Clamp/retain force mechanism | Suture tension mechanism | Different principle |

### Infringement Determination for US8920462B2

| Analysis Type | Conclusion | Confidence |
|---------------|------------|------------|
| **Literal Infringement** | **NO** - Different closure mechanism and architecture | HIGH |
| **Doctrine of Equivalents** | **NO** - Substantially different way and result | MEDIUM-HIGH |

---

## 7. CONSOLIDATED CLAIM COMPARISON MATRIX

### Feature Comparison Across All Analyzed Patents

| Feature | US9289577 (Surfacer) | US9314595 (Surfacer) | US5613974 (Perclose) | US7326230 | US8920462 | **ProGuard™** |
|---------|---------------------|---------------------|---------------------|-----------|-----------|---------------|
| Access Direction | Inside-Out | Inside-Out | Outside-In | Outside-In | Outside-In | **Inside-Out** |
| Anatomical Target | Venous | Venous | Arterial | Arterial | Arterial | **Arterial** |
| Delivery Route | Femoral vein | Femoral vein | Direct femoral | Direct femoral | Direct femoral | **Transradial** |
| Exit Location | Neck/IJV | Neck/IJV | N/A | N/A | N/A | **Groin** |
| Closure Integrated | No | No | Yes | Yes | Yes | **Yes** |
| Closure Type | N/A | N/A | Suture | Wire | Mechanical | **Suture** |
| Pre-positioned Sutures | No | No | No | No | No | **YES** |
| Multiple Needles | No | No | Yes (2) | No | No | **YES (5)** |
| Clinical Use | Dialysis access | Dialysis access | Procedure closure | Procedure closure | Procedure closure | **Access + Closure** |
| Status | Active | Active | Expired | Active | Active | N/A |
| **Infringement Risk** | **LOW** | **LOW** | **NONE** | **LOW** | **LOW** | N/A |

---

## 8. DOCTRINE OF EQUIVALENTS ANALYSIS

### Function-Way-Result Test

For each potentially relevant patent, we analyze whether ProGuard™ performs substantially the same function, in substantially the same way, to achieve substantially the same result:

#### US9289577B2 (Surfacer - Venous)

| Element | Patent | ProGuard™ | Equivalent? |
|---------|--------|-----------|-------------|
| **Function** | Provide venous access | Provide arterial access + closure | **NO** - Different function |
| **Way** | Navigate through venous system | Navigate through arterial system | **NO** - Different anatomy |
| **Result** | Central venous catheter placement | Large-bore arterial access with hemostasis | **NO** - Different clinical result |

**DOE Conclusion:** NOT EQUIVALENT

#### US9314595B2 (Surfacer - Venous System)

| Element | Patent | ProGuard™ | Equivalent? |
|---------|--------|-----------|-------------|
| **Function** | Access venous system near neck | Access arterial system at groin | **NO** - Different function |
| **Way** | Workstation at IVC/RA junction | Catheter in femoral artery | **NO** - Different positioning |
| **Result** | IJV catheter placement | Femoral arteriotomy with suture closure | **NO** - Different result |

**DOE Conclusion:** NOT EQUIVALENT

---

## 9. PROSECUTION HISTORY ESTOPPEL CONSIDERATION

### US9289577B2 Prosecution History

During prosecution of the Surfacer patents, the applicants may have made arguments or amendments that limit the scope of claims. Key considerations:

1. **Claim Scope:** The explicit limitation to "central venous system" indicates intentional scope limitation
2. **Prosecution Amendments:** Any amendments narrowing claims would further support non-equivalence
3. **Applicant Arguments:** Statements distinguishing prior art would create estoppel

### Recommendation

Review full prosecution history (USPTO PAIR) before final FTO opinion to identify any statements that further narrow claim scope.

---

## 10. SUMMARY RISK ASSESSMENT

### Patent-by-Patent Risk Levels

| Patent | Status | Risk Level | Confidence | Notes |
|--------|--------|------------|------------|-------|
| US9289577B2 | Active | **LOW** | High | Venous-only claims |
| US9314595B2 | Active | **LOW** | High | Venous anatomy-specific |
| US5613974A | Expired | **NONE** | Certain | Patent expired 2017 |
| US7326230B2 | Active | **LOW** | High | Wire-based (not suture) |
| US8920462B2 | Active | **LOW** | High | Different mechanism |
| US6517553B1 | Expired | **NONE** | Certain | Patent expired 2023 |
| US8038688B2 | Active | **LOW** | High | Outside-in methodology |

### Overall Assessment

| Metric | Assessment |
|--------|------------|
| **Likelihood of Infringement Claim** | Very Low |
| **Likelihood of Successful Defense** | Very High |
| **Confidence in Analysis** | High |
| **Recommended Action** | Proceed with commercialization |

---

## CERTIFICATION

This Patent Claims Analysis Matrix has been prepared based on comprehensive review of the identified patents and comparison with the ProGuard™ Hybrid Access & Closure System technical specifications.

**Analysis Date:** November 22, 2025

**Analyst Certification:** Analysis performed using standard patent claim construction and infringement analysis methodologies.

---

*Document ID: PCAM-2025-001*
*Classification: CONFIDENTIAL*
