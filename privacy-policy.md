# MommyLooks(마미룩스) 개인정보처리방침 / Privacy Policy

[지원 · 문의 / Support](support.md)

---

# 개인정보처리방침

MommyLooks · 최종 수정 2026년 11월 24일

## 한눈에 보기

MommyLooks(마미룩스)는 영상·소리·기록을 개발자나 다른 회사가 볼 수 있는 곳으로 보내지 않습니다. 개발자가 운영하는 서버가 없고, 회원 가입과 로그인이 없으며, 광고·분석·추적 도구를 넣지 않았습니다. 개발자는 이 앱을 쓰는 사람의 정보를 수집하지 않습니다.

## 영상과 소리

카메라 역할 기기의 영상과 소리는 QR로 등록한 모니터 기기로만 실시간으로 전달됩니다. 같은 Wi-Fi나 개인 핫스팟으로 연결하면 그 안에서만 오가고 인터넷을 거치지 않습니다. 영상과 소리는 두 기기만 풀 수 있게 암호화(AES-256-GCM)해서 보내고, 암호 열쇠는 연결할 때마다 새로 만듭니다. 등록에 쓰는 열쇠는 QR 코드로 두 기기 사이에서만 주고받으며, 카메라는 연결할 때마다 등록된 그 모니터 기기가 맞는지 확인합니다.

## 집 밖에서 보기(외부 보기)

- 처음에는 꺼져 있습니다. 카메라 폰의 설정에서 모니터마다 켜야 하고, 켜면 그때부터 최대 72시간 동안 집 밖에서 볼 수 있습니다. 연장하려면 모니터 폰에서 Face ID·지문(또는 폰 암호)으로 본인을 확인한 뒤, 카메라 폰이나 집 Wi-Fi에 있는 다른 모니터에서 승인해야 합니다.
- 두 폰 모두 사용자가 직접 설치하고 가입한 VPN 앱(Tailscale)이 있어야 합니다. 영상과 소리는 이 VPN을 거쳐 인터넷으로 오갑니다. 두 기기가 직접 이어지지 못하면 Tailscale의 중계 서버(해외에 있을 수 있음)를 거칠 수 있지만, VPN의 암호화와 이 앱의 암호화가 함께 걸려 있어 중계 서버도 내용을 볼 수 없습니다.
- 이 앱에는 Tailscale의 코드가 들어 있지 않고, 앱이 Tailscale과 따로 정보를 주고받지 않습니다. Tailscale 계정과 Tailscale이 처리하는 정보는 [Tailscale의 개인정보처리방침](https://tailscale.com/privacy-policy)을 따릅니다.
- 집 밖에서 연결한 모니터에는 녹화를 보여 주지 않습니다.

## 기기 안에만 저장하는 것

- 녹화: 녹화를 켜면 카메라 역할 기기에만 저장합니다. 저장 한도를 넘으면 오래된 것부터 자동으로 지우고, 앱에서 언제든 지울 수 있습니다.
- 내려받은 녹화: 카메라 설정에서 '녹화 보기'를 허용한 모니터만, 같은 Wi-Fi나 개인 핫스팟으로 연결했을 때 암호화된 연결로 내려받을 수 있습니다. 받은 파일은 그 모니터 기기에만 저장합니다.
- 등록 정보: 등록한 모니터의 이름과 열쇠를 기기의 안전한 저장소(iPhone 키체인, 안드로이드 키스토어로 암호화)에 보관합니다. 기기 확인과 외부 보기 연장에 쓰는 열쇠는 기기의 보안 영역(iPhone의 Secure Enclave, 안드로이드 키스토어) 안에서 만들고 밖으로 꺼내지 않습니다.
- 접속 기록과 설정: 어느 모니터가 언제 연결했는지(최근 100건, 집 밖에서 연결했는지 포함)와 앱 설정을 기기에 저장합니다.
- 외부 보기 정보: 카메라는 모니터마다 외부 보기가 끝나는 시각을, 모니터는 카메라 폰의 VPN 주소와 외부 보기 남은 시간을 기기에 저장합니다.
- 움직임·큰 소리 감지: 기기 안에서 화면의 밝기 변화와 소리의 크기만 계산합니다.

녹화 파일은 iCloud·PC 백업에 넣지 않습니다. iPhone에서 녹화가 아닌 설정과 기록은 기기 백업에 들어갈 수 있지만, 등록 열쇠는 다른 기기로 옮겨지지 않습니다. 안드로이드는 앱 데이터 전체를 백업과 새 기기로 옮기기에서 뺍니다.

## 권한을 쓰는 이유

- 카메라: 영상을 찍고, 모니터 등록 QR을 읽습니다.
- 마이크: 아기 소리를 보냅니다. 카메라 설정에서 끌 수 있습니다.
- 로컬 네트워크: 같은 네트워크에 있는 기기를 찾아 연결합니다.
- 알림: 모니터 앱이 뒤에 있을 때 움직임·큰 소리·과열·연결 상태와 외부 보기 연장 소식을 알립니다.
- Face ID·지문: 집 밖에서 외부 보기를 연장할 때 본인인지 확인합니다. 확인은 폰이 하고, 앱은 얼굴·지문 정보를 받지 않습니다.
- 사진 추가(iPhone), 저장소(안드로이드 9 이하): '사진 앱에 저장'·'갤러리에 저장'을 누를 때만 씁니다.
- 배터리 최적화 제외(안드로이드): 허용하면 모니터 화면이 꺼진 동안에도 연결을 유지합니다.

## 직접 내보낸 영상

'사진 앱에 저장'(안드로이드는 '갤러리에 저장')을 누르면 녹화가 기기의 사진 앱으로 복사됩니다. 그 뒤에는 사진 앱의 설정(iCloud 사진, Google 포토 백업 등)을 따릅니다.

## 보관과 삭제

개발자가 보관하는 정보가 없으므로 따로 삭제를 요청할 필요가 없습니다. 기기 안의 녹화와 기록은 앱에서 지울 수 있고, 앱을 삭제하면 함께 지워집니다. iPhone의 키체인에 보관한 등록 정보는 iOS 특성상 앱을 삭제해도 남을 수 있는데, 앱을 다시 설치하면 처음 실행할 때 지웁니다. Tailscale 계정과 그 정보는 Tailscale에서 관리하고 지웁니다.

모니터 폰을 잃어버렸다면 카메라 폰의 설정 → 등록된 모니터에서 그 모니터의 등록을 지우세요. 연결 중이어도 바로 끊기고, 그 폰으로는 다시 볼 수 없습니다.

## 아이의 정보

이 앱은 아이를 돌보는 보호자가 쓰는 앱입니다. 아이의 모습과 소리는 위에서 설명한 대로 보호자의 기기 사이에서만 오가며, 개발자는 받지 않습니다.

## 방침이 바뀌는 경우

이 방침을 바꾸면 앱 업데이트와 함께 이 화면과 스토어에 적은 주소에 고친 날짜와 내용을 올립니다.

## 문의

이 방침이나 앱에 대해 궁금한 점은 이메일로 보내 주세요: park.apps.world@gmail.com

---

# Privacy Policy

MommyLooks · Last updated November 24, 2026

## At a glance

MommyLooks does not send video, audio or records anywhere the developer or any other company can see them. The developer runs no servers, there is no sign-up or login, and the app contains no advertising, analytics or tracking tools. The developer does not collect information about the people who use this app.

## Video and sound

Video and sound from the device in the camera role go, in real time, only to monitor devices that were registered with a QR code. When the devices connect over the same Wi-Fi network or personal hotspot, the video and sound stay on that network and do not pass through the internet. They are encrypted so that only the two devices can decrypt them (AES-256-GCM), and new encryption keys are made for every connection. The key used for registration is exchanged only between the two devices, through the QR code, and on every connection the camera checks that it is talking to the registered monitor device.

## Watching from outside the home (remote viewing)

- Remote viewing is off at first. It has to be turned on for each monitor in the camera phone's settings, and once it is on, that monitor can watch from outside the home for up to 72 hours. To extend it, the person with the monitor phone confirms their identity with Face ID or a fingerprint (or the phone's passcode), and the extension must then be approved at home, on the camera phone or on another monitor connected to the home Wi-Fi.
- Both phones need a VPN app (Tailscale) that you install and sign up for yourself. Video and sound travel over the internet through this VPN. If the two devices cannot connect directly, the traffic may pass through Tailscale's relay servers (which may be located in other countries), but because both the VPN's encryption and this app's own encryption are applied, the relay servers cannot see the content.
- This app contains no Tailscale code and does not exchange any other information with Tailscale. Your Tailscale account and the information Tailscale processes are governed by [Tailscale's privacy policy](https://tailscale.com/privacy-policy).
- Monitors connected from outside the home cannot view recordings.

## Data stored only on your devices

- Recordings: when recording is turned on, recordings are saved only on the camera device. When the storage limit is reached, the oldest recordings are deleted automatically, and you can delete recordings in the app at any time.
- Downloaded recordings: only monitors that are allowed to view recordings in the camera settings can download them, over the encrypted connection, and only while connected over the same Wi-Fi network or personal hotspot. Downloaded files are saved only on that monitor device.
- Registration data: the names and keys of registered monitors are kept in the device's secure storage (the iPhone Keychain, or encrypted with the Android Keystore). The keys used for device verification and for extending remote viewing are created inside the device's secure area (the iPhone's Secure Enclave or the Android Keystore) and never leave it.
- Connection history and settings: which monitor connected and when (the latest 100 entries, including whether it connected from outside the home) and the app settings are saved on the device.
- Remote viewing data: the camera saves the time remote viewing ends for each monitor, and the monitor saves the camera phone's VPN address and the remaining remote viewing time.
- Motion and loud-sound detection: only changes in image brightness and the loudness of sound are calculated, on the device.

Recording files are excluded from iCloud and computer backups. On iPhone, settings and history other than recordings may be included in device backups, but registration keys are never moved to another device. On Android, all app data is excluded from backups and from transfers to a new device.

## Why the app uses permissions

- Camera: to capture video and to read the monitor registration QR code.
- Microphone: to send the baby's sound. This can be turned off in the camera settings.
- Local network: to find and connect to devices on the same network.
- Notifications: to tell you about motion, loud sounds, overheating, the connection status and remote viewing extensions while the monitor app is in the background.
- Face ID and fingerprint: to confirm that it is you when you extend remote viewing from outside the home. The phone performs the check; the app never receives face or fingerprint data.
- Add to Photos (iPhone) and Storage (Android 9 and earlier): used only when you choose to save a recording to Photos or the Gallery.
- Battery optimization exemption (Android): if you allow it, the monitor keeps its connection while the screen is off.

## Videos you export

When you choose to save a recording to Photos (on Android, the Gallery), the recording is copied to the device's photo app. From then on, the photo app's settings apply (for example, iCloud Photos or Google Photos backup).

## Retention and deletion

The developer stores no information about you, so there is nothing to ask the developer to delete. Recordings and history on your devices can be deleted in the app and are removed when you delete the app. Because of how iOS works, registration data kept in the iPhone Keychain may remain after the app is deleted; the app removes it the first time it runs after being reinstalled. Your Tailscale account and its data are managed and deleted through Tailscale.

If you lose a monitor phone, delete that monitor's registration in the camera phone's settings, in the list of registered monitors. Its connection ends immediately, even if it is connected at the time, and that phone can no longer watch.

## Children's information

This app is used by parents and caregivers who look after a child. As described above, the child's image and sound travel only between the caregivers' devices, and the developer never receives them.

## Changes to this policy

If this policy changes, the revised date and text will be published together with the app update, in the in-app policy screen and at the address listed in the store.

## Contact

If you have any questions about this policy or the app, please email: park.apps.world@gmail.com
