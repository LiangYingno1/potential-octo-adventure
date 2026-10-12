# Mr_Voz Toolkit

Termux multi-tool. UI loading → menu → raid / ddos / sms / quit.

## Cách dùng

```bash
git clone https://github.com/<you>/mr_voz.git
cd mr_voz
bash run.sh
```

Hết. `run.sh` tự cài Python nếu chưa có, rồi chạy tool.

## Modules

| # | Module | Ghi chú |
|---|---|---|
| 1 | Discord Raid | cần user token, dán vào `data/tokens.txt` |
| 2 | DDoS | 20000 request, xoay UA, proxy tùy chọn |
| 3 | SMS Spam | relay công khai, thay provider thật nếu cần |
| 4 | Quit | thoát |

## Config

- `data/tokens.txt` — Discord user tokens, 1 dòng 1 cái (tự xoay)
- `data/proxies.txt` — proxy list (tùy chọn)
- `data/uas.txt` — user-agent list
