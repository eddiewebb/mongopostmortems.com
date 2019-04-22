# MongoDB Incident Postmortems

Collection of incidents to learn from.  

## Contirbuting

If you're aware of an incident which root cause includes MongoDB issues, please submit a PR!

### Collect the Assets You'll Need
1) Company/Service logo
2) Incident Postmortem URL
3) Brief summary of incident, mongo impact.

### Update the items.toml
All Incidents live in `data/items.toml`, the format collects the assets above.

### Test locally
This site uses hugo, so you can `hugo serve` locally to make sure it renders correctly

## Incidents to *not* include
THis sit is really intended to provide insight and lessons on sclaing issues with mongo. There may be other behaviors that cause Mongo to fail, but should not be included here. 

These excluded events include:

1) Incidents caused by SSL certificate expriry on mongo
2) Incidents caused by total Infrastructure outages (i.e. network switch stopped all traffic)
