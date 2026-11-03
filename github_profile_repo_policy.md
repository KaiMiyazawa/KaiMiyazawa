# GitHub Profile Repo Policy

This repository is the source of truth for my GitHub profile presentation.

## Purpose

- Keep this repository focused on a clear self-introduction that is easy to understand from the GitHub profile page.
- Treat `README.md` as the public landing page shown at the top of `github.com/KaiMiyazawa`.
- Resumes, certificates, and images live in the private notes repository, not here.

## Branch Strategy

- Use `main` only.
- Do not use feature branches unless there is a special operational reason.
- Commit directly to `main` after checking that the public-facing result is coherent.

## README.md Role

- `README.md` is special and should stay short, readable, and high-signal.
- It should communicate who I am, what I do, and what I am currently focused on within a few seconds.
- Avoid turning `README.md` into a full resume or a long changelog.
- Prefer simple structure, low visual clutter, and clear wording over completeness.

## Content Allocation

- Put the shortest public summary in `README.md`. This is the only substantive file that is published.
- Do not add supporting files (resumes, certificates, images); the profile consists of `README.md` and this policy file.

### Resume drafts and certificates

Resume drafts, certificates, and images are **not** kept in this repository.
They live in my private notes repository, which includes this repository as a submodule.
The public/private split was reviewed on October 4, 2026. Resume text was updated
for external use, while certificates and personal details remain private.
Treat `README.md` as the public profile surface; resume publication is a separate decision.
Do not include company ownership or commissioned client work in this profile.
Keep the existing 42Tokyo badge and its destination link.

The source of truth for career history is not in this repository. Resume drafts are
derived from it and maintained in the private notes repository.

## Writing Guidelines

- Optimize for first impression and clarity.
- Prefer concise English in `README.md`.
- Keep wording factual and easy to scan.
- Avoid duplicate information across multiple files unless there is a clear audience difference.
- When in doubt, shorten rather than expand.

## Update Rules

- Before editing `README.md`, decide whether the information belongs on the profile top page or in the private notes repository.
- If a change makes `README.md` longer, confirm that the added information improves profile comprehension.
- Before adding any new file, review it as a public artifact.
- Review the repository as a public artifact, not just a private notes space.

## Operating Principle

The repository should function as a well-maintained public profile repository, with `README.md` as the front page; this policy file is the only other document.
