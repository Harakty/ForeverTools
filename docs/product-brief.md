# Product brief

## User outcome

One small Windows window for launching WoW Forever, consulting a popularity-based addon catalogue when needed, and managing a deliberately chosen set of addons.

## Planned acceptance criteria

- The user selects the game folder once and can launch that installation.
- The catalogue supports search, categories, most-downloaded sorting and votes/ratings only when real source data is available.
- Each metric names its source and indicates whether it covers the whole addon project or a Forever release.
- Only releases explicitly matching the selected client are offered for installation; declared support does not imply local verification.
- Installs, updates and removals are user-triggered. Newly discovered addons are never installed automatically.
- Required dependencies are explained before changes are applied.
- Backups and rollback cover the addon files changed by ForeverTools; they do not silently promise recovery of all game or character settings.
- Discovery notifications, recommendation feeds and recurring installation prompts are excluded.

## Current milestone

Publish a genuine project description and prepare the API-access application. No functional application is included in this milestone.

## Provider questions to resolve

1. Is this personal launcher/catalogue use case eligible for CurseForge API access?
2. What request and download quotas apply, and what costs can arise?
3. Are ratings or votes populated for WoW addons with Forever releases?
4. Which API game-version type identifies Forever, and can download counts be scoped to those releases?
5. How should API credentials be handled in an approved personal desktop application?
6. What, if any, API-data caching is permitted?

## Source and privacy boundaries

Public source contains the specification and project page. Applicant contact details, API keys, filled application forms, logs and operational evidence remain outside the repository. Addon archives are downloaded from approved original providers and are not rehosted here.

## Next milestone

After API-access conditions are known: choose the runtime, implement the launcher and catalogue, and validate installation and rollback on a small user-selected addon set.
