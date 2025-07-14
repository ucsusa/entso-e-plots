# ENTSO-E plots
Some analysis and plots of generation data in Spain from ENTSO-E, for a blog post about the outage on April 28, 2025.

## Source

ENTSO-E, [Actual Generation per Production Type](https://transparency.entsoe.eu/generation/r2/actualGenerationPerProductionType/show?name=&defaultValue=false&viewType=GRAPH&areaType=BZN&atch=false&datepicker-day-offset-select-dv-date-from_input=D&dateTime.dateTime=01.05.2025+00:00|CET|DAYTIMERANGE&dateTime.endDateTime=01.05.2025+00:00|CET|DAYTIMERANGE&area.values=CTY|10YES-REE------0!BZN|10YES-REE------0&productionType.values=B01&productionType.values=B02&productionType.values=B03&productionType.values=B04&productionType.values=B05&productionType.values=B06&productionType.values=B07&productionType.values=B08&productionType.values=B09&productionType.values=B10&productionType.values=B11&productionType.values=B12&productionType.values=B13&productionType.values=B14&productionType.values=B20&productionType.values=B15&productionType.values=B16&productionType.values=B17&productionType.values=B18&productionType.values=B19&dateTime.timezone=CET_CEST&dateTime.timezone_input=CET+(UTC+1)+/+CEST+(UTC+2)) for Spain.

### Data must be downloaded manually

ENTSO-E has an API but is transitioning to a new system. Rather than integrate either the old or new API, data must be downloaded manually. A free ENTSO-E account is needed. Then select `Export Data` and select the annual CSV. Save the resulting file to the folder `data`.

## Using

The repo contains a Jupyter notebook for all plots and analysis.