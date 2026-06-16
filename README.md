# Bias Detection Pipeline --- Outcome Bias Analysis Report

## 1. Objective

Determine whether recruiter decisions introduce bias based on candidate
demographics after receiving AI-generated scores.

The analysis focuses on whether candidates from different groups
experience different outcomes:

-   Unlock decisions
-   Rejection rates
-   Hiring progression

when controlling for AI score levels.

------------------------------------------------------------------------

## 2. Research Question

**Do candidates from certain demographic groups get rejected or accepted
at different rates despite having similar AI scores?**

------------------------------------------------------------------------

## 3. Key Finding 1 --- Country Is a Strong Predictor of Recruiter Decisions

### Recruiter Decision Results

  Country   Rejection Effect                 Direction
  --------- -------------------------------- ------------------
  Nigeria   +2.7 coefficient approximately   Higher rejection

### Interpretation

Nigerian candidates experience higher rejection rates even after
accounting for AI scoring patterns.

This indicates:

-   Recruiter decisions are not fully aligned with AI scores
-   Additional factors influence decision-making

------------------------------------------------------------------------

## 4. Key Finding 2 --- AI Scores Are Not Driving Recruiter Decisions

### Model Performance

Recruiter Decision Models:

**Pseudo R²:**

≈ 0.06 -- 0.25

### Interpretation

AI score contribution is:

-   Weak
-   Inconsistent
-   Sometimes positively associated with rejection

Expected relationship:

> Higher score → lower rejection

Observed:

> Higher score does not consistently protect candidates from rejection.

### Conclusion

Recruiter decisions appear to operate independently from AI scoring
signals.

------------------------------------------------------------------------

## 5. Key Finding 3 --- Unlock Stage Is Not a Meaningful Filtering Point

### Results

-   Unlock rates: \~90%--100% across groups
-   Model performance: Pseudo R² ≈ 0.07--0.12

### Interpretation

Unlocking is almost automatic and does not meaningfully differentiate
candidates.

The stronger bias signal appears during rejection decisions.

------------------------------------------------------------------------

## 6. Key Finding 4 --- Large Unobserved Decision Layer Exists

Recruiter models explain only:

-   6%--25% of decision variation

Meaning:

-   75%--94% of decisions are explained by unknown factors.

Potential drivers:

-   Communication style
-   Accent perception
-   Language nuance
-   Cultural fit perception

### Interpretation

Country may be acting as a proxy variable rather than a direct cause.

------------------------------------------------------------------------

## 7. Outcome Bias Conclusions

The analysis indicates:

-   Recruiter decisions are not consistently aligned with AI scoring.
-   Nigerian candidates experience higher rejection despite higher AI
    scores.
-   The decision stage introduces additional bias beyond the scoring
    stage.
-   Recruiter judgment contains significant unexplained variation.

------------------------------------------------------------------------

# 8. Recommendations --- Recruiter Decision Pipeline

## Immediate

### 1. Investigate high-score rejections

Review:

-   Nigerian candidates
-   Above median AI scores
-   Rejected candidates

Purpose:

Identify potential inconsistent decision patterns.

------------------------------------------------------------------------

## Short-Term

### 2. Introduce decision guardrails

Example:

High-score candidates should require justification before rejection.

### 3. Audit recruiter behavior

Compare decisions across recruiters while controlling for:

-   Candidate score
-   Country
-   Experience

------------------------------------------------------------------------

## Long-Term

### 4. Replace country-based assumptions

Measure actual factors:

-   Language proficiency
-   Communication clarity
-   Response quality

Avoid relying on country as a proxy.

------------------------------------------------------------------------

# Final Outcome Bias Takeaway

The recruiter decision stage shows evidence of outcome bias. While AI
scoring assigns higher scores to some groups, recruiter decisions do not
consistently reflect those scores.

The largest concern is the disconnect between AI evaluation and human
decision-making, suggesting that bias enters primarily during
interpretation and final selection decisions.

