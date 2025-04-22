# Posthog

- Open-source Product Analytics
- Offers: session recording, feature flags, event tracking, A/B testing and more into a single tool

## Core concepts

1. Events:

- Any user action: page view, button click, API call
- Custom events can be tracked via SDS (e.g., `posthog.capture()`)

2. Properties:

- Metadata attached to events or users
- Examples: `event.properties.page`, `user.properties.plan`

3. Users (persons)

- Unique users identified by `distinct_id`
- Can attach properties like name, email, subscription type

4. Sessions / Recordings

- Replays of user sessions for UX insights
- Tied to user behavior (scrolls, clicks, etc)

5. Feature flags

- Toggle features on/off for segments (e.g., 50% of users)
- Used for experiments or gradual rollouts

6. Funnels

- Track conversion steps (e.g., signup -> tutorial -> purchase)
- Analyze where users drop off

7. Dashboards

- Visualize data (retention, trends, user paths, etc)
- Fully customizable and shareable

8. Cohort

- Group of users based on behavior or properties
- Useful for targeting with feature flags or analysis

9. Plugins/integrations

- Extend functionality (e.g., import/export data, enrich events)
- Common ones: GeoIP, data pipelines
