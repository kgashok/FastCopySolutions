# AI Content / Plagiarism Analysis Report

## Methodology

This analysis examines each submission for indicators commonly associated with AI-generated content:

1. **AI-typical phrases** - Terms frequently used by language models (e.g., "significantly", "comprehensive", "it's important to note", "delve into")
2. **Structural formality** - Numbered sections, formal headings (Overview, Conclusion, Implementation)
3. **Comparison tables** - Professionally formatted feature comparison tables
4. **Technical jargon density** - Heavy use of terms like "overhead", "branching", "loop unrolling", "Duff's Device"
5. **Writing style** - Polished, error-free prose vs. natural student writing with minor imperfections

---

## Risk Assessment Table

| Submitter | AI Phrase Count | Structure Score | Has Tables | Word Count | **AI Risk Level** | **Confidence** |
|-----------|-----------------|-----------------|------------|------------|-------------------|----------------|
| **JANANI S** | 19 | 6 | Yes | 593 | **HIGH** | 90% |
| **PRADEEP G** | 11 | 4 | Yes | 422 | **HIGH** | 85% |
| **SIKKANDHAR BATCHA J** | 8 | 0 | Yes | 580 | **MODERATE-HIGH** | 70% |
| SATHISH R | 4 | 1 | Yes | 607 | MODERATE | 50% |
| JANANI R | 2 | 0 | Yes | 478 | LOW-MODERATE | 35% |
| INDUMATHI S | 2 | 0 | No | 180 | LOW | 25% |
| MADAN S | 0 | 0 | No | 150 | VERY LOW | 5% |
| ARUNA R | 1 | 0 | No | 322 | LOW | 15% |
| SARANYA S | 1 | 0 | No | 665 | LOW | 10% |
| ANITHA M | 0 | 0 | No | 501 | VERY LOW | 5% |
| ANUSHA S | 0 | 0 | No | 357 | VERY LOW | 5% |
| DHAMAYANTHI P | 0 | 0 | No | 586 | VERY LOW | 5% |
| KIRTHIKA R | 0 | 0 | No | 727 | VERY LOW | 5% |

---

## Detailed Analysis

### HIGH RISK Submissions

#### 1. JANANI S - **90% AI Probability**

**Red Flags:**
- Highest AI phrase count (19 instances)
- Perfect numbered section structure (1. Overview, 2. Implementation, 3. Comparison, 4. Execution Time, 5. Conclusion)
- Professional-grade comparison tables with formatting
- Uses "timeit" benchmarking with precise measurements (0.184s, 0.037s, etc.)
- Contains phrases like "significantly faster", "optimized for instruction timing", "superior choice"
- Secondary comparison table (Duff's Device vs Pythonic Approach)
- Too polished and comprehensive for typical student work

**AI-Typical Phrases Found:**
- "significantly"
- "optimized for"
- "performance-critical"
- "execution environment"
- "overhead"
- "branching"
- "loop unrolling"
- "Duff's Device"
- "high-level"
- "low-level"
- "Pythonic"
- "maintainability"
- "readability"

**Verdict:** This submission reads like a professional technical document or AI-generated comparative analysis. The structured sections, benchmark data, and polished prose are inconsistent with typical student submissions.

---

#### 2. PRADEEP G - **85% AI Probability**

**Red Flags:**
- High AI phrase count (11 instances)
- Numbered sections (1. Overview, 2. Implementation Codes, 3. Comparison, 4. Comparative Table)
- Professional comparison table format
- Uses term "gen_copy" (unusual naming, possibly AI-suggested)
- Very similar structure and phrasing to JANANI S submission
- Contains "performance-critical", "simulated execution environments", "significantly impact"

**AI-Typical Phrases Found:**
- "significantly"
- "performance-critical"
- "execution environment"
- "overhead"
- "branching"
- "loop unrolling"
- "Duff's Device"

**Similarity Note:** PRADEEP G and JANANI S submissions share:
- Identical section structure (Overview → Implementation → Comparison)
- Same comparison table format
- Similar phrasing about "loop condition checks"
- Both mention "Duff's Device-style" approach

**Verdict:** Likely AI-generated or copied from the same AI source as JANANI S.

---

#### 3. SIKKANDHAR BATCHA J - **70% AI Probability**

**Red Flags:**
- Moderate AI phrase count (8 instances)
- Restates problem statement verbatim (copy-paste)
- Technical language without personal explanation
- Uses exact constraint wording from problem statement

**AI-Typical Phrases Found:**
- "performance-critical"
- "execution environment"
- "overhead"
- "branching"
- "loop unrolling"

**Verdict:** Appears to heavily rely on AI for technical explanations, though less polished than JANANI S or PRADEEP G.

---

### MODERATE RISK Submissions

#### 4. SATHISH R - **50% AI Probability**

**Mixed Signals:**
- Has comparison tables and structured analysis
- BUT includes unique "v1 to v4" analysis showing failed approaches
- References "Python Tutor" (specific tool, suggests personal experience)
- Explains WHY slicing violates constraints (deeper understanding)
- Stage-by-stage breakdown shows genuine engagement

**Verdict:** May have used AI for parts, but shows original thinking and deeper engagement with the problem. More likely AI-assisted rather than AI-generated.

---

#### 5. JANANI R - **35% AI Probability**

**Observations:**
- Low AI phrase count
- Restates execution constraints (copy-paste from problem)
- Code appears original
- Limited explanation suggests less AI involvement

**Verdict:** Likely original work with possible AI assistance for code structure.

---

### NEW SUBMISSIONS

#### 6. INDUMATHI S - **25% AI Probability** [NEW]

**Observations:**
- Very brief submission (approx. 180 words of explanation)
- Mentions "Duff's device" and "loop unrolling" - could be from research or AI
- Simple, functional explanation without elaborate prose
- Code is clean but explanation is minimal

**AI Indicators Found:**
- "loop unrolling optimization technique"
- "reduce the overhead of loop control"
- "inspired by Duff's device"

**Verdict:** Low risk. The brevity and lack of elaborate structure suggests original work. Technical terms could be from legitimate research. The minimal explanation is more consistent with a student who understands the code but didn't invest heavily in documentation.

---

#### 7. MADAN S - **5% AI Probability** [NEW]

**Observations:**
- **Code only** - no prose explanation at all
- Only inline comments (standard programming comments)
- No technical jargon in explanations
- No comparison tables or structured sections
- Test case shows practical understanding

**Verdict:** Very low risk. This is the opposite of AI-generated content - it's purely functional code without the elaborate explanations that AI typically produces. The inline comments are practical rather than educational.

---

### LOW RISK Submissions (Likely Original)

#### 8. ARUNA R - **15% AI Probability**
- Contains logic errors (human mistakes)
- Informal code comments ("//both source and destination index is 0")
- Errors in implementation suggest genuine student struggle
- **Irony:** The errors make this more likely to be original work

---

#### 9. SARANYA S - **10% AI Probability**
- **Unique creative element:** Hindu mythology analogy (Arjuna/Karnan story)
- Personal voice in writing ("I ask my robot to copy")
- Fruit box analogy shows original teaching approach
- Story mapping table is creative and original
- Error handling in code (input validation) shows thought

**Verdict:** Highly likely original. Creative analogies are characteristic of human thinking, not typical AI output.

---

#### 10. KIRTHIKA R - **5% AI Probability**
- **Unique creative element:** FastCopy robot children's story
- "Planets in Space" narrative is unconventional
- Personal voice ("little robot named FastCopy")
- Story-based teaching approach is original
- Signed "Ms.R.Kirthika.AP/ECE" (faculty member perspective)

**Verdict:** Highly likely original. The creative storytelling approach is distinctly human.

---

#### 11. ANITHA M, ANUSHA S, DHAMAYANTHI P - **5% AI Probability each**
- No AI-typical phrases detected
- Code-focused submissions without elaborate prose
- Natural imperfections in formatting
- Direct, functional explanations

**Verdict:** Appear to be genuine student work.

---

## Similarity Analysis

### Suspected Common Source: JANANI S ↔ PRADEEP G

| Element | JANANI S | PRADEEP G |
|---------|----------|-----------|
| Section 1 | "1. Overview" | "1. Overview" |
| Section 2 | "2. Implementation Codes" | "2. Implementation Codes" |
| Section 3 | "3. Comparison of Execution Logic" | "3. Comparison of Execution Logic" |
| Table headers | "Feature / Normal Copy / Fast Copy" | "Feature / Normal Copy / Fast Copy" |
| Key phrase | "Duff's Device-style loop-unrolled approach" | "Duff's Device-style" |

**Conclusion:** These two submissions likely used the same AI prompt or one copied from the other.

---

## Summary

| Risk Category | Submitters | Recommendation |
|---------------|------------|----------------|
| **HIGH (70-90%)** | JANANI S, PRADEEP G, SIKKANDHAR BATCHA J | Further investigation recommended; consider oral examination |
| **MODERATE (35-50%)** | SATHISH R, JANANI R | May be AI-assisted; acceptable if policy allows AI assistance |
| **LOW (5-25%)** | INDUMATHI S, MADAN S, ARUNA R, SARANYA S, KIRTHIKA R, ANITHA M, ANUSHA S, DHAMAYANTHI P | Likely original work |

---

## New Submissions Summary

| Submitter | AI Risk | Notes |
|-----------|---------|-------|
| **INDUMATHI S** | LOW (25%) | Brief but functional; mentions Duff's device which could be from research |
| **MADAN S** | VERY LOW (5%) | Code-only submission with no prose - opposite of AI pattern |

---

## Recommendations

1. **For HIGH risk submissions:** Consider requiring an oral defense or follow-up explanation of their code
2. **Establish AI policy:** Clarify whether AI assistance is permitted for explanations vs. code
3. **SARANYA S and KIRTHIKA R:** Despite lower grades, their creative approaches demonstrate original thinking that should be valued
4. **ARUNA R:** The errors in this submission, while lowering the grade, actually increase confidence in originality
5. **MADAN S:** While low on explanation, the code-only approach is clearly not AI-generated and shows practical competence

---

## Updated Statistics

| Metric | Value |
|--------|-------|
| Total Submissions Analyzed | 13 |
| HIGH Risk | 3 (23.1%) |
| MODERATE Risk | 2 (15.4%) |
| LOW/VERY LOW Risk | 8 (61.5%) |

---

*Analysis completed on: January 10, 2026*
*Note: This analysis uses heuristic indicators and should not be treated as definitive proof of AI usage. Human judgment should be applied in all cases.*
