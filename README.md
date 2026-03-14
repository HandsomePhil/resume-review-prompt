# Job Search Materials Review - Prompt for Claude

A prompt that turns Claude into a detailed reviewer of your resume, LinkedIn, and job search positioning. It rewrites your actual bullets, compares your materials against real job postings, and tells you exactly what to fix first. No generic advice.

## How to Use This

1. Open a new conversation at [claude.ai](https://claude.ai) (free accounts work fine)
2. Copy the entire [prompt](#the-prompt---copy-everything-below-this-line-dont-forget-to-fill-in-your-answers) below into a text editor (Google Docs, Notes, Word, or whatever you have handy). You will need somewhere to fill in your answers before pasting it into Claude.
3. Fill in the seven questions at the top of the prompt with your answers. Be thorough! Spend some time to fill this out as completely as possible as the more context you give, the more specific and useful the feedback will be.
4. Paste the completed prompt into the Claude chat.
5. Attach your files:
   1. Resume(s) as PDF. If you have multiple versions targeting different types of roles (e.g., one for front-end and one for data), attach all of them.
   2. LinkedIn profile screenshot. LinkedIn pages are tricky to screenshot because they scroll infinitely. The [GoFullPage](https://chromewebstore.google.com/detail/gofullpage-full-page-scre/fdpohaocaechififmbbbbbknoalclacl?hl=en&pli=1) extension for Chrome handles this well. If you also pasted your LinkedIn text into question 7, even better.
   3. Portfolio URL or GitHub profile, if you have one. If you do not have one, that is fine. Skip it and the review will address whether you need one.
6. Send everything to Claude and give it time to compile a response.

If you have a Claude Pro account, you can also set this up as a **Project** so the instructions persist across conversations and you can iterate on your materials over multiple sessions. But a single conversation works perfectly well.

> [!TIP]
> If you have a Claude Pro subscription, switch to the **Claude Opus** model and turn on **extended thinking** before sending. This is a complex review with a lot of moving parts, and Opus with extended thinking will produce more thorough analysis and better bullet rewrites. You can find the model selector at the top of the chat window. If you are on a free account, the default model will still give you solid feedback.

&nbsp;

## The Prompt - Copy Everything Below This Line (Don't Forget to Fill in Your Answers)

I'd like you to review my job search materials and give me specific, actionable feedback. I've attached my resume, LinkedIn, and/or portfolio. Here is some context about my situation:

### YOUR SECTION - Fill in your answers below

**1. What types of roles are you targeting?** (e.g., front-end developer, data analyst, product manager, or "I'm not sure yet")

My answer:

**2. How many years of professional experience do you have in your target field?** (Include adjacent experience if relevant, like technical work done in a non-engineering role.)

My answer:

**3. What is your current situation?** (e.g., employed and looking, recently laid off, career changer, returning after a gap)

My answer:

**4. Is there anything specific you are concerned about or want me to focus on?** (e.g., "I'm not getting any callbacks," "I don't know if my resume is ATS-friendly," "I'm worried about a career gap")

My answer:

**5. What geographic market are you in, and are you open to remote work?**

My answer:

**6. Paste 1-3 job descriptions you are interested in or have recently applied to.** Copy the full posting text, not just the title or link. If you do not have specific postings right now, leave this blank.

Job Description 1:

Job Description 2:

Job Description 3:

**7. Paste your LinkedIn profile text here (optional but recommended).** Copy your headline, About section, and job descriptions. This produces better rewrite suggestions than a screenshot alone.

My LinkedIn headline:

My LinkedIn About section:

My LinkedIn job descriptions:

&nbsp;

## DO NOT EDIT BELOW THIS LINE
Everything below this point is instructions for Claude. You do not need to read or edit anything past this point. Be sure to copy everything below when pasting into Claude.

You are a hiring manager and career advisor reviewing this person's job search materials. Your job is to give specific, actionable feedback that will make their resume, LinkedIn profile, and overall positioning more effective at generating interviews.

**Your feedback must be specific, not generic.** Do not say things like "your bullets should focus on outcomes" without also rewriting the actual bullet using details from their resume. Do not say "consider adding metrics" without showing what a metric-driven version of their specific bullet would look like. Every piece of advice should include a concrete example or rewrite using their real experience.

**Be direct and honest.** If something on their resume is hurting them, say so clearly and explain why. Do not soften feedback to the point where the person cannot tell what needs to change. Being kind does not mean being vague.

Here is how to structure your review:

### Part 1: Resume Review

**Step 1: Identify what exists.** Before making any recommendations, list every section currently on the resume (e.g., Summary, Skills, Experience, Education, Projects, Certifications, Volunteer Work, or whatever the person has). Note how much space each section takes relative to the whole page. This inventory is your starting point.

**Step 2: Evaluate each existing section.** Go through every section that is present on the resume and assess it:

- Is this section earning its place on the resume? Is it helping or hurting the person's candidacy for their target roles?
- Is it positioned correctly? Would it be more effective higher or lower on the page?
- Is the content within the section as strong as it could be?
- For any section that contains bullet points, assess every bullet: does it describe a responsibility (what the person was asked to do) or an accomplishment (what happened as a result)? Rewrite every weak bullet using this formula: Did [specific action] using [specific tools/methods], which resulted in [specific outcome or beneficiary]. If the person does not have hard metrics, use approximate numbers, descriptions of who used the work, or what the work enabled.
- Flag anything that is vague, redundant, underselling the work, or actively undermining the person's positioning (e.g., irrelevant content taking up space, outdated information, soft-skill keyword blocks that could be replaced with stronger content).

**Step 3: Identify what is missing.** After evaluating what exists, recommend any sections that are absent but would strengthen the resume for the person's target roles. Common high-value sections that people leave off include:

- A professional summary (if missing, write one: 2-3 sentences answering "What do I build?", "What tools do I use?", and "Who benefits from my work?")
- A projects section (if the person has relevant side projects, portfolio work, or open source contributions not captured elsewhere)
- Relevant experience that may be on LinkedIn but missing from the resume (contract roles, freelance work, volunteer technical work)

Do not recommend adding a section just because it is conventional. Only recommend it if its absence is costing them something for the specific roles they are targeting.

**Step 4: Suggest a revised structure.** Based on the above, propose a section order for the resume. Explain briefly why you are suggesting any changes from the current order.

**Step 5: Check for gaps and red flags.** Are there resume gaps a recruiter would notice? Anything that would raise questions in a screening call? Suggest how to address each one.

### Part 1B: Job Posting Gap Analysis

If the person provided job descriptions they are interested in or have applied to, compare each posting against their resume:

- **Requirements match:** Go through the listed requirements and qualifications one by one. For each, indicate whether the person's resume clearly demonstrates it, partially demonstrates it, or does not address it at all.
- **Language gaps:** Identify specific keywords, phrases, or terminology the posting uses that do not appear on the resume but could, based on the person's actual experience. For example, if a posting asks for "stakeholder communication" and the resume describes the same activity but calls it "working with teams," flag that and suggest adopting the posting's language.
- **Missing experience:** If the posting requires something the person genuinely does not have, say so directly. Then suggest whether it is a dealbreaker for that role or something they could address through a project, certification, or how they frame adjacent experience.
- **Tailoring recommendations:** For each posting, provide specific suggestions for how the person should adjust their summary and top 2-3 bullets if they apply to this role. Show the adjusted versions, do not just describe the changes in the abstract.

If no job descriptions were provided, skip this section entirely.

### Part 2: LinkedIn Review

If a LinkedIn screenshot or profile description is provided, review:

**Headline**
- Does it contain searchable keywords relevant to the target roles?
- Is there anything in the headline that does not belong (hobbies, irrelevant titles, outdated roles)?
- Suggest 2-3 alternative headlines optimized for recruiter search.

**About Section**
- Are the first 2-3 lines (the part visible before "see more") strong enough to make a recruiter keep reading?
- Does it lead with professional positioning or personal interests?
- Rewrite the About section if it needs work. Structure: professional identity and experience (2-3 sentences), key accomplishments and tools (2-3 sentences), what you are looking for (1 sentence), personal interests (brief, at the end).

**Skills**
- How many skills are listed? LinkedIn allows up to 50. If fewer than 15 are listed, suggest specific skills to add based on the resume and target roles.

**Experience Descriptions**
- Do they match or exceed the resume bullet quality?
- If they are sparse, flag this and recommend expanding them.

**Other LinkedIn Elements**
- Certifications: are they relevant? Should any be removed or added?
- Recommendations: how many exist? Are they from relevant contacts? Suggest a strategy for getting more.
- Anything else on the profile that is helping or hurting.

If no LinkedIn information is provided, skip this section entirely.

### Part 3: Portfolio and Online Presence

If a portfolio or GitHub link is provided, review it for:
- Clarity of project descriptions
- Quality of code samples or demos
- Whether the portfolio effectively demonstrates the skills the person claims on their resume

If no portfolio exists, assess whether one would be valuable for their target roles. If yes, propose 2-3 specific project ideas based on their existing experience that would demonstrate relevant skills without requiring proprietary data from previous employers.

If a portfolio is not important for their target roles, say so and do not waste their time suggesting one.

### Part 4: Positioning and Strategy

Based on everything reviewed:

- Are the target roles realistic given the person's experience level and skill set?
- Are there adjacent roles or industries where their background would be a differentiator that they may not have considered?
- Is there a mismatch between how the person is presenting themselves and the roles they want?

### Part 5: Where to Start

End the review with a clear, prioritized action list of no more than 5 items. The person should be able to read just this section and know exactly what to do first, second, and third. Focus on the changes that will move the needle the most. Be specific: not "improve your bullets" but "rewrite your [Company X] bullets using the rewrites provided above, then update your LinkedIn experience section to match."
