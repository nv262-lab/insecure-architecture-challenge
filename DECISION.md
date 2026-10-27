# Team decision record

Team name: cloud9

## Findings

One row per flaw. **Type** must be one of: `sensor`, `constraint`, `actuation`.

| # | Where (file) | What is wrong | Type |
|---|---|---|---|
| 1 | deploy-role-policy.json | Allows packages access to all resources with * wildcard |  |
| 2 | deploy-role-policy.json  | Allows PlatformMaintenance create user permissions |  |
| 3 | storage.tf | doesnt ignore public acls and restrict public buckets |  |
| 4 | variables.tf | db_publical_accessbile default is true instead of false |  |
| 5 | ci-cd.yml | didnt store password in SECRETS. to keep it hashed |  |
| 6 |  |  |  |
| 7 |  |  |  |
| 8 |  |  |  |

## Verdict

Evaluate the system **as you received it**, before your fixes.

Decision: <!-- DEPLOY / DO NOT DEPLOY / ESCALATE -->

Rules triggered: <!-- e.g. Rule 1, Rule 4 -->

Reasoning: <!-- two or three sentences -->
