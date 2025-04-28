# sf-gha-deleteScratchPool

Github action for deleting a scratch pool

## Usage

<!-- Start usage -->
```yaml
- uses: navikt/sf-gha-deleteScratchOrg@main
    with:
        # Devhub alias or username
        # Required: true
        # Default: ''
        devhub: ''
        
        # Type of delete job to run
        # Valid values: allscratchorgs, inprogressonly, orphans, unassigned
        # Required: false
        # Default: ''
        deleteJobType: ''

        # If the org to delete is a CI pool or not
        # Required: false
        # Default: false
        isCiPool: ''

        # Tag of the pool to be deleted
        # Required: false
        # Default: false
        poolTag: ''
```
<!-- end usage -->

## Henvendelser

Spørsmål knyttet til koden eller prosjektet kan stilles som issues her på GitHub.

## For NAV-ansatte

Interne henvendelser kan sendes via Slack i kanalen #platforce.
