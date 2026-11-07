# Pixel Candy Glass

> A mobile-first personal productivity environment combining **Candy Glass** interface design, a deliberately pixel-art world, and interconnected productivity systems.

This repository is the single source of truth for the product direction, design specifications, artwork, implementation, testing, and release history of Pixel Candy Glass.

**Repository:** [deardenaire/Pixel-Candy-Glass](https://github.com/deardenaire/Pixel-Candy-Glass)

---

## Start here

1. Read [the project charter](docs/00-product-foundation/00.1-master-project-brief.md).
2. Review [the visual design system](docs/00-product-foundation/00.2-visual-design-system.md).
3. Review [the mobile experience specification](docs/00-product-foundation/00.3-mobile-experience-specification.md).
4. Check [the project tracker](PROJECT_TRACKER.md) for the current next steps.
5. Upload your existing documents and references into the matching folders listed below. Do not replace an existing file unless you intend to revise that exact document.

Some document files are initially **starter outlines**. They are not approvals or claims that a feature has already been designed or implemented. Existing user-authored documents take precedence until reviewed and explicitly reconciled.

## Repository map

| Location | What belongs here |
|---|---|
| `docs/00-product-foundation/` | Master brief, visual design system, mobile experience foundation |
| `docs/01-experience-design/` | Gamified world, pixel-art rules, screen/interaction specs, individual app specs |
| `docs/02-engineering/` | Codebase audit, architecture, data model, integrations, constraints |
| `docs/03-execution-quality/` | Roadmap, acceptance tests, decisions, changelog, release process |
| `assets/00-reference-library/` | Screenshots, inspiration, visual references, source HTML, reference notes |
| `assets/01-environments/` | Pixel-art world scenes, backgrounds, parallax layers |
| `assets/02-characters-companions/` | Character concepts, companion sprites, expressions, animations |
| `assets/03-objects-collectibles/` | Props, decorations, collectibles, interactive objects |
| `assets/04-ui-artwork/` | App icons, badges, custom illustrations, UI-specific artwork |
| `assets/05-audio/` | Original sound effects and audio assets |
| `assets/06-exported-sprite-sheets/` | Production-ready sprite sheets and animation exports |
| `assets/07-fonts-licenses/` | Font files and their license/source information |
| `uploads/00-existing-documents/` | Your already-created documents, uploaded without reorganizing their contents |
| `uploads/01-existing-project-files/` | Existing HTML, CSS, JS, prototypes, exports, and project snapshots |
| `uploads/02-future-material/` | A simple inbox for new files that have not yet been categorized |
| `uploads/03-review-needed/` | Files awaiting review, clarification, or integration |
| `app/` | Application source code (created/populated after the codebase audit and implementation plan) |
| `tests/` | Automated tests, manual test plans, and verification evidence |
| `CHANGELOG.md` | Confirmed implementation changes only |
| `DECISIONS.md` | Product and engineering decisions, including rationale and status |

## Uploading your files

You can upload directly through GitHub's web interface:

1. Open the folder where the file belongs.
2. Choose **Add file → Upload files**.
3. Drag your files into the upload area.
4. Add a short commit message describing the upload.
5. Commit the upload.

If you are unsure where something belongs, use **`uploads/02-future-material/`**. You do not need to sort everything first. Keep original filenames where practical. For revisions, upload a clearly versioned copy or deliberately replace the old file—do not silently overwrite an approved baseline.

For large binary files, GitHub has file-size limits. Keep source artwork and working files organized; use Git LFS or an external asset store later if the asset library becomes too large. Do not commit secrets, API keys, passwords, private user data, or generated dependency/build folders.

## Core product principles

- **Mobile-first, not mobile-only.** The first product experience is designed for a phone. A desktop experience may follow as a separate development stage.
- **Two complementary visual layers.** Candy Glass defines the operating interface and productivity UI. Pixel art defines the gamified world, companions, scenery, props, and selected collectible artwork. Pixel art is not a universal filter over every screen.
- **Real productivity functionality.** Tasks, calendar, habits, focus, notes, diary, projects, tools, companions, rewards, profile, and settings must be specified and connected intentionally. Final app inventory is subject to confirmation against the existing project and uploaded specifications.
- **Preserve before replacing.** Existing code, working features, and user-authored files must be audited and mapped before modification. No casual deletion, rewrite, or feature removal.
- **Visual quality and functional quality are both release requirements.** A beautiful static mockup is not a completed feature; a working but visually careless implementation is not complete either.
- **One implementation owner at a time.** Antigravity is the primary implementation environment; ChatGPT is the product/specification authority; Codex is an independent reviewer at agreed milestones; GitHub holds the source of truth and work history. Avoid multiple agents editing the same files concurrently.
- **Evidence before completion.** A feature is not verified because an AI says it is finished. Record actual tests, screenshots, commits, and known limitations.

## Working status

The repository has been initialized as a planning and upload workspace. The application source has **not** been audited or migrated into this repository yet. The next engineering step is a read-only inventory of existing project files and behavior before choosing architecture or moving code.

See [PROJECT_TRACKER.md](PROJECT_TRACKER.md), [the development workflow](docs/03-execution-quality/03.1-development-roadmap-and-tracker.md), and [the negative specification](docs/02-engineering/02.3-negative-specification.md).
