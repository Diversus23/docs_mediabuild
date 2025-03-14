---
icon: file
order: 200
---

# ОверлейныйТекст (OverlayText)

Указывает текст, который будет вставлен в видео. Текст может быть изменен в процессе создания видео. Строка.

**Также текст может содержать формулы (без кавычек)**

`"%sys_time[dd.mm.yy hh:nn:ss]%"` : текущая системная дата.  
`"%frame_count%"` : количество кадров (фреймов).  
`"%time_full%"` : время в текущем фрейме в формате hh:mm:ss:cc  
`"%time_sec%"` : time of the current frame, in seconds with 2 decimals  
`"%time_100ns%"` : time of the current frame, in 100 nano-seconds units  
