# Drone Soccer Trainer

瀏覽器版足球無人機訓練與競賽模擬器。

製作人：李宇軒 / Xuan

## 功能

- 自由飛行模式
- 30 級飛行操作訓練
- 3v3 Drone Soccer 競賽模式
- 進攻手 / 防守手角色分工
- AI 電腦難度 1～10 級
- 犯規、得分與每局量化統計
- BO1 / BO3 / BO5 / BO7 系列賽
- 中場休息時間可設定
- 多人連線房間
- USB FPV 遙控器 / Gamepad API
- Mode 2 軸向設定
- 鍵盤操作
- Z 快捷鍵重置無人機

## 操作

直接開啟網站即可使用。

建議使用最新版 Chrome 或 Edge。

### 鍵盤

- W / S：前進 / 後退
- A / D：左右
- 方向鍵：依目前飛行模式控制
- Z：重置無人機

### FPV 遙控器

支援可被瀏覽器 Gamepad API 辨識的 USB FPV 遙控器。
可在遙控器設定中調整軸向、反向、死區與重置按鍵。

## GitHub Pages

此專案使用純前端 HTML / JavaScript，可直接透過 GitHub Pages 發布。

Pages 設定：

- Source: Deploy from a branch
- Branch: main
- Folder: /(root)

網站入口為 `index.html`。

## 注意

多人連線使用 WebRTC / PeerJS 信令，因此連線功能需要網路。
USB 遙控器與部分瀏覽器功能建議在 HTTPS 環境使用。

## Author

李宇軒 / Xuan