### Local-first software: Collaboration without sacrificing control

💿 Traditional **installed applications** give you control over your stuff, but
limit you to a single device, so it's clumsy to work with others. And it's your job to make sure the
data on your fragile hardware is backed up somewhere.

🌨 **Cloud applications** let you collaborate in real time and from different devices. But you can't
use them at all when you're offline. And you no longer have control over your own stuff — the
software provider does. You lose access to it if they go out of business. Or if they decide to
discontinue the service. Or if there's a problem with your credit card.

👍 **[Local-first applications](http://inkandswitch.com/local-first.html) give you the best of both
worlds:**

|                          | 💿<br/>installed apps | 🌨<br/>cloud apps | 👍<br/>local-first apps |
| ------------------------ | :-------------------: | :--------------: | :---------------------: |
| 🐇 fast                  |          ✅           |        ⛔        |           ✅            |
| 🖐 responsive            |          ✅           |        ⛔        |           ✅            |
| 🚙 no network dependency |          ✅           |        ⛔        |           ✅            |
| 📦 no provider lock-in   |          ✅           |        ⛔        |           ✅            |
| 👪 collaboration         |          ⛔           |        ✅        |           ✅            |
| 🔑 team permissions      |          ⛔           |        ✅        |           ✅            |
| 🌩 online backup          |          ⛔           |        ✅        |           ✅            |
| 🔃 continuous updates    |          ⛔           |        ✅        |           ✅            |

---

The repositories you'll find here provide tools to make it easier to build secure, distributed applications in the
browser, with no need for a single centralized server.

<table>
<tr>
<td>

<img src='https://raw.githubusercontent.com/local-first-web/branding/main/svg/lf-auth.svg'
width='500'/>

</td>
<td>

[@localfirst/auth](https://github.com/local-first-web/auth) provides decentralized authentication
and authorization for team collaboration, using a secure chain of cryptographic signatures.

</td>

<tr>
<td>

<img src='https://raw.githubusercontent.com/local-first-web/branding/main/svg/lf-relay.svg'
width='500'/>

</td>
<td>

[@localfirst/relay](https://github.com/local-first-web/relay) is a tiny service that helps
local-first applications connect with peers on other devices. It can run in the cloud or on any
device with a known address.

</td>
</tr>

</tr>
<tr>
<td>

<img src='https://raw.githubusercontent.com/local-first-web/branding/main/svg/lf-state.svg'
width='500'/>

</td>
<td>

[@localfirst/state](https://github.com/local-first-web/state) is an automatically replicated Redux
store that gives your app offline capabilities and secure peer-to-peer synchronization superpowers.

</td>
</tr>

</table>
