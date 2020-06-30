must add a config file with recipient and sender and a token pickle file with credentials

How to schedule cron job:
crontab -e

30 09 * * * /home/pi/workspace/nurseryEmailSender/sendEmail.sh

Sends an email every day at 9.30
