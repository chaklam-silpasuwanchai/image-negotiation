# Between: Negotiating Emotional Images with Generative AI

## Research Concept

Between is an image-based reflection application for adults experiencing low mood. Its central interaction is **image negotiation**: the system presents an imperfect visual representation, and the user selects, rejects, corrects, or transforms it. AI assists with visual production but does not diagnose the user or interpret the image.

The proposed contribution is an interaction technique for using representational mismatch with AI as a resource for emotional articulation and agency.

## 1. Research Questions

**RQ1.** How does negotiating with an AI-generated image affect a person's ability to articulate an emotional experience compared with selecting an existing image or generating an image from text?

**RQ2.** How do the three image interactions affect perceived agency, authorship, representational accuracy, emotional burden, and reflective depth?

**RQ3.** What benefits, breakdowns, and safety concerns arise when people use generative images to reflect on experiences of low mood?

## 2. Research Objectives

1. **Design an image-negotiation interaction** that allows people to select, reject, correct, and transform AI-generated emotional images without giving interpretive authority to the AI.
2. **Empirically compare three interaction approaches:** selecting existing images, generating images from text, and negotiating through iterative visual correction.
3. **Develop design implications** for emotionally safe, agency-preserving generative-AI systems for personal reflection and mental wellbeing.

## 3. Related Work

### Image-Based and Art-Based Reflection

Visual art can help people externalize experiences that are difficult to communicate verbally. The value does not necessarily come from artistic quality; it can emerge through creation, observation, personal meaning-making, and discussion. A meta-analysis of 15 randomized trials reported reductions in depressive symptoms following visual art therapy, although the authors rated the evidence as low quality. This supports further study while cautioning against premature clinical claims.

Imagery rescripting provides another relevant foundation. It involves deliberately changing distressing mental representations to introduce safety, support, alternative outcomes, or new perspectives. Between adapts the underlying idea of transforming an image but does not present itself as a clinical imagery-rescripting intervention.

### Generative AI and Creative Mental-Health Support

Recent work has explored AI-generated art, narratives, therapeutic homework, and multimodal dialogue. TherAIssist examined human–AI support for art-therapy homework and client–practitioner collaboration. PracticeDAPR investigated AI-supported education for novice art-therapy practitioners rather than direct emotional support for clients.

A CHI 2026 study used a generative-AI probe to investigate visuals and narratives for youth emotion regulation with 20 clinicians. Clinicians viewed generative media as a possible bridge for emotional expression but warned that vivid, unpredictable, or poorly aligned outputs could trigger users or reinforce maladaptive thinking. A related multimodal art-activity system explored AI dialogue about a user's drawing, with experts highlighting risk management, personalization, and direct visual interaction as open design challenges.

### Research Gap

Existing systems commonly emphasize image generation, image analysis, conversational guidance, or therapist support. Less attention has been given to **representational disagreement**: what happens when an AI image is not correct and the user must identify and repair the mismatch.

Between therefore treats AI error as a potential reflective resource. The system asks, “What did this image get wrong?” rather than “What does this image reveal about you?” This preserves ambiguity and positions the user as the authority on meaning.

## 4. Methodology

### Study Overview

The project will use a mixed-methods, three-condition experiment followed by semi-structured interviews. It will evaluate reflective interaction rather than clinical treatment efficacy.

### Participants

- Approximately **90 adults**, with about 30 participants per condition. The final sample should be determined by an a priori power analysis.
- Participants must be at least 18 years old and comfortable using English and digital image tools.
- Recruitment will seek people who report recent experiences of low mood but will not require a clinical diagnosis.
- A short depression questionnaire, such as the PHQ-8, may characterize the sample at baseline. It will not be used by the application to diagnose participants.
- Recruitment should aim for diversity in gender, age, ethnicity, artistic confidence, prior AI use, and prior experience with mental-health support.
- The study requires institutional ethics approval, a distress protocol, trained research staff, and clear professional-support pathways.

People facing an immediate mental-health crisis should not participate in the experiment and should instead receive appropriate support information. Exact safety and exclusion procedures must be developed with the ethics board and a qualified clinical collaborator.

### Apparatus

Participants will use the Between prototype on the same model of tablet or laptop in a private study space. The application will record interaction events with consent, including:

- images presented and selected;
- prompts and image revisions;
- corrections chosen or written by the participant;
- time spent at each stage;
- number of regenerations and rejected images;
- whether the participant paused, skipped, hid, or deleted content.

The system will include content safeguards, a clearly visible stop control, private-by-default storage, and deletion controls. The AI will not label emotions, infer diagnoses, or assign symbolic meanings to colors, objects, or composition.

### Experimental Conditions

Participants will be randomly assigned to one of three between-subject conditions:

1. **Image selection:** Participants choose from a curated set of ambiguous images and explain their choice.
2. **Text-to-image generation:** Participants describe their current experience and receive a generated image, which they then discuss.
3. **Image negotiation:** Participants choose an initial image, identify what it gets wrong, and iteratively correct or transform visual elements before reflecting on the result.

A between-subject design reduces learning and emotional carryover between conditions. The same onboarding, session duration, reflection topic, visual style, and final prompts will be used across conditions as far as possible.

### Procedure

1. Obtain informed consent and explain that the system is a research prototype, not a therapist.
2. Collect demographics, prior AI and art experience, artistic self-confidence, and baseline mood measures.
3. Ask the participant to identify a recent, manageable experience of low mood. Instructions will explicitly discourage choosing traumatic or overwhelming experiences.
4. Conduct the assigned image-reflection activity for approximately 10–15 minutes.
5. Collect immediate post-task measures.
6. Ask the participant to write a short description of the experience and what they currently need.
7. Conduct a 20–30 minute semi-structured interview about expression, accuracy, agency, discomfort, surprise, and perceived value.
8. Debrief the participant, offer deletion of all generated material, and provide relevant support resources.

### Measurements

#### Primary Outcomes

- **Emotional articulation:** specificity, differentiation, and elaboration in participants' written descriptions, coded by independent researchers using a preregistered rubric.
- **Perceived agency:** the extent to which participants felt in control of the process and final representation.
- **Representational fit:** how accurately the final image reflected the participant's experience.

#### Secondary Outcomes

- perceived authorship and ownership;
- depth of reflection;
- emotional granularity;
- immediate affect before and after the activity;
- cognitive and emotional workload;
- comfort, trust, and willingness to reuse the system;
- number and type of image corrections;
- safety events, unwanted imagery, and reasons for stopping or rejecting content.

Validated instruments should be used where suitable. New items for concepts such as representational fit should be treated as exploratory and reported transparently rather than presented as validated scales.

### Quantitative Analysis

- Compare the three conditions using regression or ANOVA, depending on the measures and their distributions.
- Control for preregistered covariates such as baseline mood, artistic confidence, and previous generative-AI experience.
- Use corrected pairwise comparisons to examine selection versus generation, generation versus negotiation, and selection versus negotiation.
- Report effect sizes and confidence intervals, not only statistical significance.
- Analyze whether agency or representational fit mediates the relationship between condition and emotional articulation only if the sample size and preregistered analysis support such a test.

### Qualitative Analysis

Interview transcripts and open-ended responses will be analyzed using reflexive thematic analysis. Likely areas of attention include:

- using mismatch to discover emotional distinctions;
- negotiating authorship with AI;
- productive ambiguity versus confusing ambiguity;
- feeling seen versus feeling misrepresented;
- emotional distancing and emotional intensification;
- fixation on AI suggestions;
- privacy, trust, and unwanted interpretation.

At least two researchers should discuss the developing analysis and document interpretive decisions. Image-edit histories can be examined alongside interview accounts to reconstruct how meaning developed during each session.

## 5. Expected Findings and Analysis

The image-negotiation condition is expected to produce greater perceived agency, representational fit, and articulation than one-shot text-to-image generation. Its advantage may not come from producing a more attractive or emotionally accurate image. Instead, participants may discover meaning while explaining why the initial image is wrong.

Image selection may be the easiest and least demanding condition, particularly for people experiencing low energy. It may support recognition but provide fewer opportunities for transformation. Text-to-image generation may feel personalized and engaging but could reduce ownership, anchor participants to the AI's first suggestion, or produce imagery that is overly literal or emotionally intense.

Expected qualitative themes include:

- **Mismatch as articulation:** correcting errors gives participants language for subtle emotional distinctions.
- **Control over interpretation:** participants value being able to reject AI suggestions without being told what an image means.
- **AI as material rather than authority:** AI is most acceptable when treated as editable creative material.
- **Different needs at different energy levels:** choosing may work better during low-energy moments, while active transformation may support deeper reflection when capacity is higher.
- **Ambivalence and risk:** some participants may experience AI-generated imagery as intrusive, generic, uncanny, or emotionally amplifying.

These are hypotheses, not predetermined conclusions. Negative and null findings will be important for identifying when image negotiation is inappropriate or unnecessarily burdensome.

## 6. Discussion

The study can contribute the concept of **image negotiation** to HCI: a form of human–AI interaction in which representational error is intentionally surfaced and made editable. Rather than optimizing the system to infer a user's emotional state, the design supports users in discovering and expressing their own interpretation.

The anticipated results may show that personalization alone is insufficient. A generated image can look personalized while still reducing agency if the system's representation dominates the interaction. Meaningful control may require explicit opportunities to reject, correct, and retain ambiguity.

The work also raises broader questions about AI authority. Mental-health interfaces can unintentionally make computational outputs appear psychologically authoritative. Between counters this by avoiding diagnosis and symbolic interpretation, marking generated images as proposals, and repeatedly returning interpretive control to the user.

### Design Implications

1. Design AI emotional representations as **proposals**, not assessments.
2. Ask users what a representation gets wrong before asking what it means.
3. Support low-effort selection as well as higher-effort creation and transformation.
4. Preserve the original and transformed images rather than implying that negative emotion must be erased.
5. Make rejection, stopping, hiding, and deletion first-class interactions.
6. Evaluate agency, emotional burden, and harmful breakdowns alongside usability and engagement.

### Limitations

- A brief laboratory activity cannot demonstrate treatment of depression.
- Self-reported low mood is not equivalent to a clinical diagnosis.
- AI output varies, making exact replication difficult.
- Participants willing to discuss emotions with AI may not represent the wider population.
- Cultural meanings of visual metaphors may limit generalization.
- Short-term articulation does not necessarily lead to sustained wellbeing.

The application should therefore be described as a reflective wellbeing tool unless later clinical research establishes safety and effectiveness. Future work could examine longer-term use, therapist-mediated use, cultural differences, accessibility, and whether people develop more effective personal strategies for choosing between image selection, drawing, and AI generation.

## References

- Han, Y. et al. (2024). *The effects of visual art therapy on adults with depressive symptoms: A systematic review and meta-analysis*. International Journal of Mental Health Nursing. https://doi.org/10.1111/inm.13331
- Jin, Y. et al. (2025). *Art psychotherapy meets creative AI: An integrative review positioning the role of creative AI in art therapy process*. Frontiers in Psychology. https://doi.org/10.3389/fpsyg.2025.1548396
- Yang, M. et al. (2025). *PracticeDAPR: An AI-based Education-Supported System for Art Therapy*. Proceedings of the ACM on Human-Computer Interaction, 9(2). https://doi.org/10.1145/3711112
- Yoo, D. et al. (2026). *Generative AI and Creative Mediums for Youth's Emotion Regulation: An Interview Study with Clinicians*. CHI 2026. https://doi.org/10.1145/3772318.3790909
- *Imagery rescripting as a short intervention for symptoms associated with mental images in clinical disorders: A systematic review and meta-analysis*. https://pubmed.ncbi.nlm.nih.gov/37738780/
- *Exploring a Multimodal Chatbot as a Facilitator in Therapeutic Art Activity*. DIS 2026 Companion. https://doi.org/10.1145/3802974.3809425
