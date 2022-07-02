# Whatsapp-Bulk-Messenger

Whatsapp Bulk Messenger automates the sending of bulk text messages via Whatsapp Web. The program runs through a list of numbers provided in `numsbers.txt` file and then tries to send a prediefined message from the `message.txt` file to each number in the list.



# Requirements

*  Python >= 3.6
*  Chrome headless is installed by the program automatically

# Setup

1. Install python - >=v3.6
2. Run `pip install -r requirements.txt`

# Steps

1. Enter the message you want to send inside `message.txt` file.
2. Enter the list of numbers line-separated in `numbers.txt` file.
3. Run `python automator.py`.
4. Once the program starts, you'll see the message in message.txt and count of numbers in the numbers.txt file.
5. After a while, Chrome should pop-up and open web.whatsapp.com.
6. Scan the QR code to login into whatsapp.
7. Press `Enter` to start sending out messages.
8. Sit back and relax!

## Note
 **The current program is limited to sending only TEXT message**