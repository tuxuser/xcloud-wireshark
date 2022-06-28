# xCloud Wireshark Dissector

This repo contains a wireshark dissector to view xHomestraiming RTP traffic.

## Requirements:

- Lua 5.2 (Other versions dont work)
- luagcrypt (https://github.com/Lekensteyn/luagcrypt)

## Setup

1. Install the plugin in wireshark
2. Go to Preferences -> Protocols -> XCLOUD-RTP
3. Enter the SRTP key obtained during the handshake (more info below)

## How do i obtain the SRTP key?

The SRTP key is exhanged on the start of the session. You can obtain this using mitm software like Fiddler.