# roomescape-bunker-firebase
* Firebase의 functions, firestore, storage 관련 코드들

## How To
### Install Firebase CLI
* https://firebase.google.com/docs/cli?hl=ko 참고
* `firebase login` 으로 로그인하면 준비 완료

### Fuctions deploy
* `firebase deploy --only functions`

### Firestore deploy
* `firebase deploy --only firestore`
	* Rules나 Indexes 변경시에도 위 명령어로 배포해야함
	* `firestore` 대신 `firestore:rules` / `firestore:indexes`로 룰/인덱스만 배포도 가능

### Storage Rule deploy
* `firebase deploy --only storage`
