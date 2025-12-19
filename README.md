# The burden and management of sleep disturbance in children with atopic dermatitis: A retrospective matched cohort study in England 
Codelists, exposure/outcome definitions and algorithms for "Incidence, management, and impact of sleep disturbance in children and adolescents with atopic dermatitis: a retrospective matched cohort study in the UK" study by Momentum Data.

## Quality control
All the codelists utilised for data extraction underwent the rigorous quality control process utilised by Momentum Data for multiple real world evidence studies. This process consisted of manual code list generation by a coding expert with a clinical background. The list was then independently reviewed by a second coding expert. The lists then went through an automated quality control process to identify any potential formatting errors or coding inconsistencies. During the data extraction process, high frequency codes were independently reviewed by a third reviewer to ensure that the most commonly used codes correctly match the clinical entity they are being used to identify. A fourth quality control step looks for overlap between code or case definitions where multiple definitions are possible e.g., biochemical disease markers and clinical diagnosis codes for a condition. Finally once variables were generated, the frequency and pattern of variable prevalence was compared with known data from previous analysis in other independent datasets and published literature. Any inconsistencies were reviewed and investigated as appropriate.

All of the conditions and medications mentioned below will use diagnostic codes recorded in primary care **only** (Read V2, Read CTV3 and SNOMED).

## Algorithms for case identification

### Active Atopic Dermatitis
Atopic Dermatitis (AD) will be identified and defined using a validated AD case definition.[^1] AD case identification will use a combination of AD specific diagnosis codes and two or more AD treatment prescribed on different dates, within 365 days of each other. AD is considered to remain active until 365 days after the final prescription in a period of ongoing prescribing.

## Atopic Dermatitis
- People identified with a specific diagnosis code for [Atopic Dermatitis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/0402c36e3628604fa4df5b0254d76b0449f1bda0/Conditions/AD%20(Atopic%20Dermatitis))

### AD treatments

- [Emollients](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Emollients)

#### Topical Steroids:
  - [Mild topical steroids](https://github.com/MomentumData/Momentum-Data-Codelists/tree/9d049bfbc698dc5678acd29ce171ab26219e0279/Treatments/Mild%20Topical%20Steroids)
  - [Moderate topical steroids](https://github.com/MomentumData/Momentum-Data-Codelists/tree/ef02573cf3e17ed460e566567c3e265552183661/Treatments/Moderate%20Topical%20Steroids)
  - [Potent topical steroids](https://github.com/MomentumData/Momentum-Data-Codelists/tree/7bca89f6071339cf1ef97990141a69662f9db3b1/Treatments/Potent%20Topical%20Steroids)
  - [Very potent topical steroids](https://github.com/MomentumData/Momentum-Data-Codelists/tree/f4a35c5bba40c485c13234695477aa9107bbe6af/Treatments/Very%20Potent%20Topical%20Steroids)

- [Topical calcineurin inhibitors](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Topical%20Calcineurin%20Inhibitors)
  
- [Topical anti-infective treatments](https://github.com/MomentumData/Momentum-Data-Codelists/tree/834e32214b94f6e56133fb25bdd9696be350a083/Treatments/Topical%20Anti-Infectives)
  
#### Systemic immunosuppressant treatments:
  - [Methotrexate](https://github.com/MomentumData/Momentum-Data-Codelists/tree/d5b18be4932e2467067cf1bb028ef7b92ecb2c58/Treatments/Methotrexate)
  - [Azathioprine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/d5b18be4932e2467067cf1bb028ef7b92ecb2c58/Treatments/Azathioprine)
  - [Mycophenolate](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Mycophenolate%20Mofetil)
  - [Ciclosporin](https://github.com/MomentumData/Momentum-Data-Codelists/tree/d5b18be4932e2467067cf1bb028ef7b92ecb2c58/Treatments/Ciclosporin)
  - Biologics:
    - [Dupilumab](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Dupilumab)

#### Phototherapy Referral
- [Phototherapy](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Conditions/Phototherapy)

#### Dermatology Referral
Any of:
- [Specialist Dermatology Referral](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Care%20Use/Specialist%20Dermatology%20Referral)
- [Specialist Dermatology Review](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Care%20Use/Specialist%20Dermatology%20Review)

### AD severity
AD severity will be defined using AD treatments utilizing a validated definition which has been previously implemented using primary care records.[^2] 
- AD is considered mild, by default.
- AD is considered moderate, following the prescription of a second potent topical steroid treatment (including very potent topical steroids) within one year or a first topical calcineurin inhibitor.
- AD is considered severe, at the first prescription of a systemic immunosuppressant treatment (ciclosporin, azathioprine, mycophenolate, methotrexate and biologics), phototherapy or a dermatology referral.
  
For an individual patient with active AD, severity can change during the study follow-up: once fulfilling criteria for moderate AD, cases remain as moderate unless they develop severe AD. When fulfilling criteria for severe AD, cases remained as severe for the remainder of their follow-up.

## Baseline characteristics

### Asthma
- [Asthma](https://github.com/MomentumData/Momentum-Data-Codelists/tree/d5b18be4932e2467067cf1bb028ef7b92ecb2c58/Conditions/Asthma)

### Atopic comorbidity
Any of:
- [Asthma](https://github.com/MomentumData/Momentum-Data-Codelists/tree/d5b18be4932e2467067cf1bb028ef7b92ecb2c58/Conditions/Asthma)
- [Allergic rhinitis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Conditions/Allergic%20Rhinitis)
- [Urticaria](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Conditions/Urticaria)

### Allergic comorbidity
Any of:
- [Asthma](https://github.com/MomentumData/Momentum-Data-Codelists/tree/d5b18be4932e2467067cf1bb028ef7b92ecb2c58/Conditions/Asthma)
- [Allergic rhinitis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Conditions/Allergic%20Rhinitis)
- [Urticaria](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Conditions/Urticaria)
- [Food Allergy](https://github.com/MomentumData/Momentum-Data-Codelists/tree/ebd4281822835a905a31d2d857179dc4f9433f5b/Conditions/Food%20Allergy)

### Autism
- [Autism](https://github.com/MomentumData/Momentum-Data-Codelists/tree/726d21351f09487d25365505dfa564602e7af4af/Conditions/Autism)

### Attention Deficit Hyperactivity Disorder (ADHD)
- [ADHD](https://github.com/MomentumData/Momentum-Data-Codelists/tree/726d21351f09487d25365505dfa564602e7af4af/Conditions/ADHD%20(Attention%20Deficicit%20Hyperactivity%20Disorder))

### Inflammatory Bowel Disease
Any of:

### Rheumatoid/Autoimmune Comorbidity
Any of:

### Family History of Atopy
- [Family History of Atopy]()

## Outcomes

### Sleep disturbance
People identified with a diagnosis code for for [sleep disturbance](https://github.com/MomentumData/Momentum-Data-Codelists/tree/0402c36e3628604fa4df5b0254d76b0449f1bda0/Conditions/Sleep%20disturbance)

### Sensitivity Analysis - Sleep disturbance not attributed to Asthma
People identified with a diagnosis code for [sleep disturbance](https://github.com/MomentumData/Momentum-Data-Codelists/tree/cb5741c150989c29ac56b9ee0b3eed0d6e1350f4/Conditions/Sleep%20Disturbance%20not%20attributed%20to%20Asthma), from a subset which excludes any codes that mention asthma.

### Medications used for sleep disturbance

#### Non-sedating antihistamines
- [Acrivastine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/cf233c9a54e4ebf1cad6f512d032a0937a5b4a0a/Treatments/Acrivastine)
-	[Bilastine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Bilastine)
-	[Cetirizine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Cetirizine)
-	[Desloratadine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Desloratadine)
-	[Fexofenadine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/de5089f7fd8fc554bad122ebd2851852b2cb25b9/Treatments/Fexofendadine)
-	[Levocetirizine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Levocetirizine)
-	[Loratadine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Loratadine)
-	[Mizolastine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Mizolastine)
-	[Rupatadine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Rupatadine)

#### Sedating antihistamines
-	[Alimemazine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Alimemazine)
-	[Azatadine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Azatadine)
-	[Chlorphenamine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Chlorphenamine)
-	[Clemastine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Clemastine)
-	[Cyproheptadine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Cyproheptadine)
-	[Dexchlorpheniramine]()
-	[Dimetindene]()
-	[Diphenhydramine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Diphenhydramine)
-	[Diphenylpyraline]()
-	[Hydroxyzine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Hydroxyzine)
-	[Ketotifen](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Ketotifen)
-	[Mebhydrolin]()
-	[Meclozine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Meclozine)
-	[Mequitazine]()
-	[Oxatomide]()
-	[Phenindamine]()
-	[Pheniramine]()
-	[Promethazine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Promethazine)

#### Melatonin
People identified with a prescription code for [melatonin](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e8a444d1e201658c22794f711c528acc2a59575f/Treatments/Melatonin)

## Secondary outcomes

# References
[^1]: de Lusignan S, Alexander H, Broderick C, et al. Epidemiology and management of atopic dermatitis in England: an observational cohort study protocol. BMJ Open 2020;10(9):e037518. doi: 10.1136/bmjopen-2020-037518
[^2]: Tippu Z, Correa A, Liyanage H, et al. Ethnicity Recording in Primary Care Computerised Medical Record Systems: An Ontological Approach. J Innov Health Inform 2017;23(4):920. doi: 10.14236/jhi.v23i4.920 [published Online First: 2017/03/28]
