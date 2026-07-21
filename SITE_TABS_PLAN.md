# Perry Portfolio Site Tabs Plan

This site should feel like a professional personal resume first, with project
depth available when visitors intentionally click into it.

## 1. About

Current homepage.

Purpose:

- Fast positioning: Software Engineer / QA Lead.
- Short professional profile.
- Core strengths.
- Small amount of personality, but not private memory.

Keep public AI wording restrained. Prefer:

- automation
- internal tooling
- knowledge systems
- developer workflow
- QA process improvement

Avoid prominent public wording such as:

- lifelong companion
- digital version of myself
- private AI memory
- dating/relationship memory

## 2. Resume

Current state:

- Top/sidebar resume button downloads `assets/Perry_Liao_Resume.pdf`.
- Resume tab should also download the same file for now.

Next upgrade:

- Add a dedicated `resume.html` page with print-friendly styling.
- Keep PDF regenerated from `resume.html`.
- Add English and Traditional Chinese variants later if needed.

## 3. Portfolio

Suggested sections:

- QA Automation & Internal Tooling
- Self-hosting Lab
- CI/CD and Production Debugging Case Studies
- Side Product: PHP + yt-dlp Downloader
- ShelterLand / freelance web work when ready

Each project should have:

- Problem
- Role
- Tech stack
- What was built
- Result / lesson learned
- Screenshots or sanitized diagrams if possible

Avoid leaking company internals, private repos, client data, or sensitive
infrastructure details.

## 4. Notes

Purpose:

- Public technical notes and learning logs.
- Good for SEO and showing engineering thinking.

Suggested categories:

- Linux / self-hosting
- Jenkins / CI/CD
- QA debugging notes
- API / integration issues
- Product and automation ideas

Do not publish raw personal diary, private AI memory, or workplace-sensitive
incident details.

## 5. Contact

Current state:

- Contact tab opens email.

Next upgrade:

- Add a compact contact section with email, GitHub, LinkedIn, location, and
  collaboration interests.
- Optional contact form only if there is a reliable backend or static form
  provider.

## Implementation Order

1. Keep this single-page version stable.
2. Add real Portfolio section with 2-3 polished case studies.
3. Add a public Notes page only after there are several publishable posts.
4. Split into separate pages when content becomes too large for one homepage.
