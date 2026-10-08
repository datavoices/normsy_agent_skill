# Normsy Civic Agent

A standalone Civic Agent skill distributed as a Claude plugin and repository marketplace. The package includes instructions and a bundled Normsy manual, without an MCP server or backend dependency.

## Layout

- `.claude-plugin/marketplace.json`: marketplace catalog.
- `plugins/normsy-civic-agent/`: installable plugin, including its manifest, README, and skill.
- `docs/`: knowledge-base provenance and behavioral validation scenarios.

## Install from the repository marketplace

Add `datavoices/normsy_agent_skill` in Claude's plugin settings, then install Normsy Civic Agent. Disable any separately uploaded copy of the same skill while testing.

## Submit to the public directory

Open https://claude.ai/directory/manage and select **Submit new → Plugin bundle**.

- Repository: `https://github.com/datavoices/normsy_agent_skill`
- Plugin path: `plugins/normsy-civic-agent`
- Branch: `main` (or the branch selected by the publisher).

The plugin includes a `LICENSE` file and declares `AGPL-3.0-or-later` in its manifest, matching the license headers in the Normsy backend. Validate in the portal, complete the listing, data handling and compliance forms, and submit for review. Submission requires an eligible paid Claude account and a connected GitHub account with push access. The repository must be public before publication.

## Validation and updates

If Claude Code is available, run `claude plugin validate ./plugins/normsy-civic-agent`. The developer portal performs additional checks. Follow `docs/VALIDATION.md` for behavioral scenarios. Raise the manifest version when releasing updates.

The knowledge-base provenance is recorded in `docs/source-snapshot.json`. Excluded content includes books and conditional guidance. The plugin does not send data to a Normsy service or store conversation data itself.

## Documentation

- https://claude.com/docs/plugins/submit
- https://claude.com/docs/plugins/pre-submission-checklist

## License

GNU Affero General Public License, version 3 or any later version (AGPL-3.0-or-later). See [LICENSE](LICENSE).
