# PCP

Updates for parsers used ----> 

WhatsApp:

Original command -----  python ./src/whatsapp_parser.py --session_token "<|endoftext|>" --delta_h_threshold 4 --user_name <user_name> --time_format "%d/%m/%y, %H:%M" ------ update to:

python ./src/whatsapp_parser.py --session_token "<|endoftext|>" --delta_h_threshold 4 --user_name <user_name> --time_format "%d/%m/%y, %H:%M %p" ------ to account for AM PM format
