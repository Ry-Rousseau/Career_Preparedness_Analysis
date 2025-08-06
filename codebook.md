# Variable Codebook

## Demographic and Background Variables

| Variable Name | Description |
|---------------|-------------|
| country | Country of respondent |
| sector | Industry sector of respondent |
| gender | Gender of respondent |
| age | Age category of respondent |
| prep_level | Career Preparedness Index (0-10)|
| qual_reasons | Qualitative reasons for responses |

## Personality Variables

| Variable Name | Description |
|---------------|-------------|
| pers_extraverted_enthusiastic | Personality trait: Extraverted, enthusiastic |
| pers_critical_quarrelsome | Personality trait: Critical, quarrelsome |
| pers_dependable_self-disciplined | Personality trait: Dependable, self-disciplined |
| pers_anxious_easily_upset | Personality trait: Anxious, easily upset |
| pers_open_to_new_experiences_complex | Personality trait: Open to new experiences, complex |
| pers_sympathetic_warm | Personality trait: Sympathetic, warm |
| pers_disorganized_careless | Personality trait: Disorganized, careless |
| pers_reserved_quiet | Personality trait: Reserved, quiet |
| pers_calm_emotionally_stable | Personality trait: Calm, emotionally stable |
| pers_conventional_uncreative | Personality trait: Conventional, uncreative |

## Emotional and Workplace Variables

### Emotional Statements - Fast Choice (es_*)

| Variable Name | Group | Subgroup | Statement |
|---------------|-------|----------|-----------|
| es_fgen | Emotional | General | I'm ready for my next step |
| es_ftra_des | Emotional | Transformation | I want a new start |
| es_ftra_aut | Emotional | Transformation | I've got freedom to change |
| es_fcnt_com | Emotional | Containers | I'm comfortable where I am |
| es_fcnt_psy | Emotional | Containers | I feel like my voice is heard |
| es_fcon_soc | Emotional | Connection | Others influence my decisions |
| es_fbal_anx | Emotional | Balance | I'm anxious about change |
| es_fres_fin | Emotional | Resources | I'm financially motivated |
| es_fcont_imp | Emotional | Control | I believe in myself |
| es_fjou_opt | Emotional | Journey | I'm optimistic about the future |
| es_fcon_inc | Emotional | Connection | I feel included |
| es_fbal_sat | Emotional | Balance | I'm happy where I am |
| es_fres_ski | Emotional | Resources | I've got the skills to progress |
| es_fcont_con | Emotional | Control | I control my next step |
| es_fjou_pro | Emotional | Journey | I've set myself goals |

### Emotional Statements - Likert Scale (el_*)

| Variable Name | Group | Subgroup | Statement |
|---------------|-------|----------|-----------|
| el_lgen | Emotional | General | I'm ready for my next step |
| el_ltra_des | Emotional | Transformation | I want a new start |
| el_ltra_aut | Emotional | Transformation | I've got freedom to change |
| el_lcnt_com | Emotional | Containers | I'm comfortable where I am |
| el_lcnt_psy | Emotional | Containers | I feel like my voice is heard |
| el_lcon_soc | Emotional | Connection | Others influence my decisions |
| el_lbal_anx | Emotional | Balance | I'm anxious about change |
| el_lres_fin | Emotional | Resources | I'm financially motivated |
| el_lcont_imp | Emotional | Control | I believe in myself |
| el_ljou_opt | Emotional | Journey | I'm optimistic about the future |
| el_lcon_inc | Emotional | Connection | I feel included |
| el_lbal_sat | Emotional | Balance | I'm happy where I am |
| el_lres_ski | Emotional | Resources | I've got the skills to progress |
| el_lcont_con | Emotional | Control | I control my next step |
| el_ljou_pro | Emotional | Journey | I've set myself goals |

### Workplace/Functional Statements - Fast Choice (wfs_*)

| Variable Name | Group | Subgroup | Statement |
|---------------|-------|----------|-----------|
| wfs_fuse_skills | Workplace/functional | Lack of opportunity to use skills/abilities | I can use my skills |
| wfs_flearn_dev | Workplace/functional | Learning and development | I have opportunities to learn |
| wfs_fcarprom | Workplace/functional | Career advancement and promotions | I can grow here |
| wfs_fmean_full | Workplace/functional | Meaning | I find my job meaningful |
| wfs_fpoorman | Workplace/functional | Poor management | My manager is poor |
| wfs_ftoxic | Workplace/functional | Toxic workplace/Company culture | The work culture is toxic |
| wfs_fexcess_wk | Workplace/functional | Excessive or too little work | I'm working too hard |
| wfs_fcollea | Workplace/functional | Disagreement or fall out with colleagues | I don't get along with my colleagues |
| wfs_fwellcomp | Workplace/functional | A better salary and financial stability | I'm well compensated |
| wfs_ffin_fair | Workplace/functional | Financial fairness | My salary is unfair compared to colleagues |
| wfs_fenjhyb | Workplace/functional | Satisfaction around hybrid working | I enjoy hybrid working |

### Workplace/Functional Statements - Likert Scale (wfl_*)

| Variable Name | Group | Subgroup | Statement |
|---------------|-------|----------|-----------|
| wfl_luse_skills | Workplace/functional | Lack of opportunity to use skills/abilities | I can use my skills |
| wfl_llearn_dev | Workplace/functional | Learning and development | I have opportunities to learn |
| wfl_lcarprom_d | Workplace/functional | Career advancement and promotions | I can grow here |
| wfl_lmean_full | Workplace/functional | Meaning | I find my job meaningful |
| wfl_lpoorman | Workplace/functional | Poor management | My manager is poor |
| wfl_ltoxic | Workplace/functional | Toxic workplace/Company culture | The work culture is toxic |
| wfl_lexcess_wk | Workplace/functional | Excessive or too little work | I'm working too hard |
| wfl_lcollea | Workplace/functional | Disagreement or fall out with colleagues | I don't get along with my colleagues |
| wfl_lwellcomp | Workplace/functional | A better salary and financial stability | I'm well compensated |
| wfl_lfin_lair | Workplace/functional | Financial fairness | My salary is unfair compared to colleagues |
| wfl_lenjhyb | Workplace/functional | Satisfaction around hybrid working | I enjoy hybrid working |

## Presentation order
Assume the questions were presented firstly any demograhpic/screener type questions including personality test, then the implicit/explicit (these were counterbalanced across participants, and statements within these blocks were presented in random order).

Our key dependent variable is our preparedness index.


## Variable Type Information

- **Fast Choice variables (es_*, wfs_*)**: Float64/Float32 - Continuous measures from fast choice responses
- **Likert variables (el_*, wfl_*)**: Integer - Likert scale responses  
- **Personality variables (pers_*)**: Integer - Categorical personality trait measures
- **Demographics**: Mixed types (object, category, float32)

## Country and Sector Codes

### Country Codes
- FR: France
- DE: DACH (Germany and Switzerland)  
- SP: Spain
- US: USA
- IT: Italy
- UK: United Kingdom

### Sector Codes
- Fin: Financial Services
- Tech: Technology
- Pharma: Pharmaceutical
- Energy: Energy

## Variable Ranges/ Discrete Values

### Scaling Differences by Variable Domain

The survey employs different scaling systems based on the construct domain being measured: **Emotional** versus **Workplace/Functional** variables. This distinction applies consistently across both response modalities (fast choice and Likert scales).

### Emotional Variables - Bipolar Scaling

Emotional constructs use bipolar scales that allow for both positive and negative orientations relative to a neutral midpoint.

#### Emotional Fast Choice Variables (es_*)
- **Scale Type**: Bipolar continuous scale
- **Range**: -100 to +100 (in practice we never see exactly -100 or +100)
- **Midpoint**: 0 (neutral)
- **Variable Count**: 15 variables
- **Interpretation**: 
  - Negative values = Disagreement/Opposition
  - Zero = Neutral/Indifferent
  - Positive values = Agreement/Alignment

**Variables and Observed Ranges:**
- es_fbal_anx: -94.44 to 98.89
- es_fbal_sat: -96.67 to 98.89
- es_fcnt_com: -98.89 to 97.78
- es_fcnt_psy: -97.22 to 98.89
- es_fcon_inc: -98.89 to 97.78
- es_fcon_soc: -98.89 to 97.78
- es_fcont_con: -96.67 to 97.78
- es_fcont_imp: -98.89 to 98.89
- es_fgen: -96.67 to 98.89
- es_fjou_opt: -96.67 to 96.67
- es_fjou_pro: -98.89 to 96.67
- es_fres_fin: -98.89 to 98.89
- es_fres_ski: -98.89 to 98.89
- es_ftra_aut: -96.11 to 98.89
- es_ftra_des: -98.89 to 98.89

#### Emotional Likert Variables (el_*)
- **Scale Type**: Bipolar ordinal scale
- **Range**: -100 to +100
- **Scale Points**: 9 discrete values (-100, -75, -50, -25, 0, 25, 50, 75, 100)
- **Variable Count**: 15 variables
- **Interpretation**: Same as fast choice emotional variables

**All el_* variables use the full -100 to +100 range with 9 scale points.**

### Workplace/Functional Variables - Unipolar Scaling

Workplace/functional constructs use unipolar scales that measure intensity of agreement from zero (strong disagreement) to maximum (strong agreement).

#### Workplace/Functional Fast Choice Variables (wfs_*)
- **Scale Type**: Unipolar continuous scale
- **Range**: 0.0 to 100.0
- **Minimum**: 0 (strongest disagreement)
- **Maximum**: 100 (strongest agreement)
- **Variable Count**: 11 variables
- **Interpretation**: 
  - 0 = Strong disagreement
  - 100 = Strong agreement
  - No negative values possible

**Variables and Observed Ranges:**
- wfs_fcarprom: 0.0 to 100.0
- wfs_fcollea: 0.0 to 100.0
- wfs_fenjhyb: 0.0 to 100.0
- wfs_fexcess_wk: 0.0 to 100.0
- wfs_ffin_fair: 0.0 to 100.0
- wfs_flearn_dev: 0.0 to 100.0
- wfs_fmean_full: 0.0 to 100.0
- wfs_fpoorman: 0.0 to 100.0
- wfs_ftoxic: 0.0 to 100.0
- wfs_fuse_skills: 0.0 to 100.0
- wfs_fwellcomp: 0.0 to 100.0

#### Workplace/Functional Likert Variables (wfl_*)
- **Scale Type**: Unipolar ordinal scale
- **Range**: 0 to 100
- **Scale Points**: 5 discrete values (0, 25, 50, 75, 100)
- **Variable Count**: 11 variables
- **Interpretation**: Same as fast choice workplace/functional variables

**All wfl_* variables use the full 0 to 100 range with 5 scale points.**

### Summary of Scale Ranges by Response Type

| Variable Group | Response Type | Scale Type | Range | Scale Points |
|----------------|---------------|------------|-------|--------------|
| Emotional (es_*) | Fast Choice | Bipolar Continuous | -100 to +100 | Continuous |
| Emotional (el_*) | Likert | Bipolar Ordinal | -100 to +100 | 9 points |
| Workplace (wfs_*) | Fast Choice | Unipolar Continuous | 0 to 100 | Continuous |
| Workplace (wfl_*) | Likert | Unipolar Ordinal | 0 to 100 | 5 points |

## Factor Analysis Variables

Factor analysis was performed to identify underlying latent constructs from the survey responses. The following factor variables were created through dimensional reduction:

### Combined Factor Variables

| Variable Name | Description |
|---------------|-------------|
| combined_factor_1 | Primary combined factor from all survey items |
| combined_factor_2 | Secondary combined factor from all survey items |
| combined_factor_3 | Tertiary combined factor from all survey items |
| combined_factor_4 | Fourth combined factor from all survey items |
| combined_factor_5 | Fifth combined factor from all survey items |

### Fast Choice Factor Variables

| Variable Name | Description |
|---------------|-------------|
| fast_factor_1 | Primary factor from fast choice (implicit) responses |
| fast_factor_2 | Secondary factor from fast choice (implicit) responses |
| fast_factor_3 | Tertiary factor from fast choice (implicit) responses |
| fast_factor_4 | Fourth factor from fast choice (implicit) responses |

### Likert Factor Variables

| Variable Name | Description |
|---------------|-------------|
| likert_factor_1 | Primary factor from Likert (explicit) responses |
| likert_factor_2 | Secondary factor from Likert (explicit) responses |
| likert_factor_3 | Tertiary factor from Likert (explicit) responses |
| likert_factor_4 | Fourth factor from Likert (explicit) responses |

### Emotional Factor Variables

| Variable Name | Description |
|---------------|-------------|
| emotional_factor_1 | Primary factor from emotional constructs |
| emotional_factor_2 | Secondary factor from emotional constructs |
| emotional_factor_3 | Tertiary factor from emotional constructs |
| emotional_factor_4 | Fourth factor from emotional constructs |

### Workplace Factor Variables

| Variable Name | Description |
|---------------|-------------|
| workplace_factor_1 | Primary factor from workplace/functional constructs |
| workplace_factor_2 | Secondary factor from workplace/functional constructs |
| workplace_factor_3 | Tertiary factor from workplace/functional constructs |
| workplace_factor_4 | Fourth factor from workplace/functional constructs |

### Personality Factor Variables

| Variable Name | Description |
|---------------|-------------|
| personality_factor_1 | Primary factor from personality trait variables |
| personality_factor_2 | Secondary factor from personality trait variables |
| personality_factor_3 | Tertiary factor from personality trait variables |

**Note**: All factor variables are standardized with mean = 0 and standard deviation = 1. Higher values indicate stronger association with the underlying latent construct represented by that factor.