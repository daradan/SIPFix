# SIP fix

The patch for solving problems in SIP: clicks, intermittent signal, increasing delay, breaking connection.

**Tested on:**
- Xiaomi Redmi 5 Plus (vince) - miui 9 android 7.*

**You can do it yourself:**
1. Needed root
2. open build.prop
3. change value on **use.voice.path.for.pcm.voip** to **false** or add (if not available) **use.voice.path.for.pcm.voip=false**
4. change value on **use.dedicated.device.for.voip** to **false** or add **use.dedicated.device.for.voip=false**
5. save changes
6. reboot phone

Фикс отсутствия голоса в приложении гугл при чтении ответов на поисковый запрос

**Вы можете это сделать сами:**
1. Необходим рут
2. открываем build.prop
3. изменяем значение в **use.voice.path.for.pcm.voip** на **false** или добавить (если не имеется) **use.voice.path.for.pcm.voip=false**
4. изменяем значение в **use.dedicated.device.for.voip** на **false** или добавить (если не имеется) **use.dedicated.device.for.voip=false**
5. сохраняем изменения
6. перезагрузить телефон
