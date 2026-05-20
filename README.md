# Lab 7 

Tim Nguyen

## Question 1

Within a GitHub Action that runs whenever code is pushed.

This catches bugs immediately on every push in a clean, consistent environment, without relying on developers to remember to run tests locally. Waiting until all development is complete makes regressions expensive and hard to trace to a specific commit.

## Question 2

No.

## Question 3

Navigation mode reloads the page and measures the entire load sequence, producing performance metrics like First Contentful Paint and Largest Contentful Paint, since it controls the load timing and can timestamp every event from request to paint. Snapshot mode audits the page in its current DOM state without reloading, which makes it useful for accessibility checks but unable to measure load performance because there is no load event to time.

## Question 4

1. Reduce unused JavaScript, which currently wastes around 1,756 KiB of bandwidth and main-thread time on code that never runs.
2. Add a lang attribute to the <html> element so screen readers can apply the correct pronunciation rules.
3. Add a meta description so search crawlers have a controlled snippet to display under the page title in results, rather than letting Google auto-generate one from arbitrary page content.