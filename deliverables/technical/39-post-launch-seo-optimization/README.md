# Post-Launch SEO Optimization

**Automation score:** 8/10
**Status:** SOP documented
**Fulfillment lane:** Post-Launch Website SEO Optimization / Technical SEO Audit / Onsite Core Content Optimization
**Cadence:** Run after every new client website launch and after major structural deployments.

## Purpose

Run a controlled SEO quality pass after a website goes live so the production domain is crawlable, indexable, measurable, accessible, conversion-ready, and documented before the site enters normal monthly fulfillment.

This SOP was formalized from the Bollinger Landscaping post-launch optimization run and should be reused as the baseline process for future launch QA.

## Required Inputs

- Live production domain and sitemap URL.
- Source repository, deployment platform, and production deployment target.
- Approved client NAP, service areas, services, images, reviews, and tracking requirements.
- Existing launch notes, known blockers, and any client-sensitive copy restrictions.
- Access confirmation for Search Console, analytics, CMS, forms, hosting, or repo systems when needed.

## Guardrails

- Verify production output, not only local or preview builds.
- Do not change DNS, billing, ownership, platform permissions, secrets, or irreversible account settings without owner approval.
- Do not publish unsupported claims, legal-sensitive copy, unapproved service-area claims, or review/rating markup that is not backed by visible content.
- Do not break forms, phone links, quote flows, review widgets, maps, navigation, or tracking while making SEO fixes.
- Every implemented change needs a commit, deployment reference, and live verification note.

## Standard Workflow

1. Confirm the production URL, repo, branch, deployment workflow, and current live build.
2. Crawl the live sitemap and record all indexable public URLs.
3. Review robots.txt, sitemap XML, canonical tags, status codes, redirects, and noindex signals.
4. Audit title tags, meta descriptions, H1s, headings, visible copy, and page intent against the approved keyword map.
5. Verify Search Console ownership, sitemap submission path, analytics tags, and conversion tracking requirements.
6. Review service pages, service-area pages, blog content, footer trust pages, and internal links for missing or weak launch content.
7. Optimize image alt text with page-specific keywords while keeping the text natural and descriptive.
8. Add or repair JSON-LD schema using valid Schema.org types that match the page purpose and visible business facts.
9. Test forms, phone links, CTAs, review links, maps, navigation, and mobile conversion paths.
10. Check performance, mobile rendering, accessibility basics, console errors, and broken assets.
11. Commit changes, deploy through the normal repo workflow, and verify the live production domain after deployment.
12. Update the post-launch run log with completed items, commits, deployment IDs, live URLs, verification counts, and remaining blockers.

## Required Output

- Live-site audit notes with the production URL and crawl scope.
- Completed fix log grouped by SEO area.
- Commit hashes and deployment IDs for every implementation batch.
- Live verification evidence for the updated production pages.
- Remaining blockers, if any, with owner and next step.
- Final handoff note confirming the site is ready to enter normal SEO fulfillment.

## Bollinger Pilot Evidence

The Bollinger Landscaping run established the reusable pattern:

- robots.txt and sitemap validation completed in commit `73708a8`.
- Google Search Console and analytics support completed in commits `cc7a988` and `0c3bc4b`.
- First post-launch blog content completed in commit `6efc13e`.
- Legal/trust-page support completed in commit `69588d5`.
- SEO alt text was implemented in commit `e70ee70` and verified across the live image set.
- LocalBusiness and Organization JSON-LD schema was implemented in commit `8473b6a` and verified on the homepage, service pages, and service-area pages.

## Human Role

- Approve visible copy changes, legal-sensitive claims, service-area claims, and major layout decisions.
- Provide or confirm access when platform, CMS, analytics, Search Console, hosting, or repo credentials are needed.
- Approve any irreversible account, DNS, billing, permission, or ownership change.

## AI Role

- Crawl the production site, classify issues, and prepare implementation-ready fixes.
- Generate page-specific alt text, schema JSON-LD, metadata recommendations, and QA checklists.
- Apply safe repo-based changes, run local validation, deploy through the approved workflow, and verify production.
- Keep the process log current so the post-launch run can be audited later.

## QA Checklist

- Sitemap URLs load with expected 200-level responses.
- robots.txt does not block production pages or rendering resources.
- Canonicals point to the preferred production URLs.
- Important pages have useful title tags, meta descriptions, H1s, and internal links.
- Images have descriptive page-specific alt text.
- JSON-LD parses cleanly and uses valid Schema.org types.
- Search Console, analytics, and conversion tracking requirements are accounted for.
- Forms, phone links, CTAs, reviews, maps, and navigation work on desktop and mobile.
- No obvious console errors, broken assets, or mobile overlap issues remain.
- Final live verification is documented before handoff.
