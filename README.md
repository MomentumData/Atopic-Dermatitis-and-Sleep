# The burden and management of sleep disturbance in children with atopic dermatitis: A retrospective matched cohort study in England 
Codelists, exposure/outcome definitions and algorithms for "Incidence, management, and impact of sleep disturbance in children and adolescents with atopic dermatitis: a retrospective matched cohort study in the UK" study by Momentum Data.

## Quality control
All the codelists utilised for data extraction underwent the rigorous quality control process utilised by Momentum Data for multiple real world evidence studies. This process consisted of manual code list generation by a coding expert with a clinical background. The list was then independently reviewed by a second coding expert. The lists then went through an automated quality control process to identify any potential formatting errors or coding inconsistencies. During the data extraction process, high frequency codes were independently reviewed by a third reviewer to ensure that the most commonly used codes correctly match the clinical entity they are being used to identify. A fourth quality control step looks for overlap between code or case definitions where multiple definitions are possible e.g., biochemical disease markers and clinical diagnosis codes for a condition. Finally once variables were generated, the frequency and pattern of variable prevalence was compared with known data from previous analysis in other independent datasets and published literature. Any inconsistencies were reviewed and investigated as appropriate.

## Algorithms for identification
All of the conditions and medications mentioned below will use diagnostic codes recorded in primary care **only** (Read V2, Read CTV3 and SNOMED).

### Atopic Dermatitis (AD)
AD will be identified and defined using a validated AD case definition.[^1] AD case identification will use a combination of AD specific diagnosis codes and two or more AD treatment prescribed on different dates.

- People identified with a specific diagnosis code for [AD](https://github.com/MomentumData/Momentum-Data-Codelists/tree/0402c36e3628604fa4df5b0254d76b0449f1bda0/Conditions/AD%20(Atopic%20Dermatitis))

### AD treatments
- [Emollients](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Emollients)

#### Topical Steroids:
  - [Very potent topical steroids]()
  - [Potent topical steroids]()
  - [Moderate topical steroids]()
  - [Mild topical steroids]()
  
- [Topical calcineurin inhibitors](https://github.com/MomentumData/Momentum-Data-Codelists/tree/04bf1598119391c98ea45550cc69cf9f6517a17b/Treatments/Topical%20Calcineurin%20Inhibitors)
  
- [Topical anti-infective treatments]()
  
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
- AD is considered moderate, following the prescription of a second potent topical steroid treatment within one year or a first topical calcineurin inhibitor.
- AD is considered severe, at the first prescription of a systemic immunosuppressant treatment (ciclosporin, azathioprine, mycophenolate, methotrexate and biologics), phototherapy or a dermatology referral.
  
For an individual patient with active AD, severity can change during the study follow-up: once fulfilling criteria for moderate AD, cases remain as moderate unless they develop severe AD. When fulfilling criteria for severe AD, cases remained as severe for the remainder of their follow-up.

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
- [Food Allergy]()

### Autism
- [Autism]()

### Attention Deficit Hyperactivity Disorder (ADHD)
- [ADHD]()

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
People identified with a prescription code for [melatonin]()

# References
[^1]: de Lusignan S, Alexander H, Broderick C, et al. Epidemiology and management of atopic dermatitis in England: an observational cohort study protocol. BMJ Open 2020;10(9):e037518. doi: 10.1136/bmjopen-2020-037518
[^2]: Tippu Z, Correa A, Liyanage H, et al. Ethnicity Recording in Primary Care Computerised Medical Record Systems: An Ontological Approach. J Innov Health Inform 2017;23(4):920. doi: 10.14236/jhi.v23i4.920 [published Online First: 2017/03/28]
