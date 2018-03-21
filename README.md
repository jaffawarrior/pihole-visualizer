I started with https://splunkbase.splunk.com/app/3023/ and made some tweaks to searches, added some drilldowns and other improvements.

To add the speedtest, move speedtest.csv to /var/www/html and add it to Cron to run every half hour:

*/30 * * * * speedtest-csv >> /var/www/html/speedtest.csv
 
![Alt text](/piHoleVis/screenshots/summary.png?raw=true "Optional Title")
![Alt text](/piHoleVis/screenshots/domain_activity.png?raw=true "Optional Title")
![Alt text](/piHoleVis/screenshots/client_activity.png?raw=true "Optional Title")
![Alt text](/piHoleVis/screenshots/pi_health.png?raw=true "Optional Title")
