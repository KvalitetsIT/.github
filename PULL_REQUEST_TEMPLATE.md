>The PR-template can be found [here](https://github.com/KvalitetsIT/.github/blob/main/PULL_REQUEST_TEMPLATE.md)

# Jira issue
Issue number: **KH-**

<hr/>

# Changes

### What has changed - and why?
<!-- required-text-start -->
Type here
<!-- required-text-end -->
# Checklist
> Til udvikling: [Udviklingshåndbog](https://kvalitetsit.atlassian.net/wiki/x/AYAcrQ)
> 
> Til hosting: [Operations guide](https://kvalitetsit.atlassian.net/wiki/x/cYAffg) 

<!-- ignore-task-list-start -->
<!-- ignore-task-list-end -->

## Vurdering

- [ ] Jeg bekræfter at ændringen ikke introducerer nye privacy-mæssige risici (privacy-by-design og by-default)
- [ ] Jeg bekræfter at ændringen ikke introducerer nye sikkerhedsmæssige risici (security-by-design og by-default)

## Implementering

- [ ] Ændringen er reviewet og godkendt af mindst én anden udvikler
- [ ] Al kode og konfiguration er under versionskontrol 
- [ ] Der er ingen credentials, API-nøgler eller hemmeligheder i kildekoden

## Test

- [ ] Ændringen er testet og virker efter hensigten
- [ ] Testmiljøet kørte kun syntetiske eller anonymiserede data - ingen persondata
- [ ] Rollback er mulig og fremgangsmåden er kendt

## Deployment

- [ ] Det er bekræftet at det er det rigtige miljø der opdateres
- [ ] Monitorering og alarmering er aktiv

<hr/>

**Remember to add label** 
 > A label should be added to this repo if:
 >  - Repo contains infrastructure components maintained by KIT
 
 `production release tested` (After the PR is tested in prod - No matter the outcome)  
 `production release no impact` (If this pr will not impact production)
