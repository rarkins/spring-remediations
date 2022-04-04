# spring-remediations

This preset helps remediate against CVE-2022-22965 within other Spring framework packages.
Any Spring framework packages which depends on a vulnerable version of `spring-beans` directly or transitively is included in this preset, to be on the safe side.

Use this preset by adding `github>renovatebot/spring-remediations` to your `extends` array in Renovate or WhiteSource Remediate:

```json
{
  "extends": ["github>renovatebot/spring-remediations"]
}
```
