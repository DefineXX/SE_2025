# Use Case Description

---

## 1. 회원가입

| Actor action(User) | System response |
| ------------ | --------------- |
|  | 1. ID, 비밀번호, 전화번호를 입력하는 화면을 보여준다. |
| 2. 비회원(Guest)은 ID, 비밀번호, 전화번호를 입력한다. 이후 회원가입 버튼을 클릭한다. |  |
|              | 3. 회원가입 완료 메세지를 출력한다. |

## 2. 로그인

| Actor action(User) | System response |
| ------------ | --------------- |
|  | 1. ID와 비밀번호를 입력하는 화면을 보여준다.  |
| 2. 관리자와 사용자는 ID와 비밀번호를 입력한다. 이후 로그인 버튼을 클릭한다. |  |
|              | 3. 홈 화면으로 이동한다. |

## 3. 로그아웃

| Actor action(User) | System response |
| ------------ | --------------- |
| 1. 로그아웃 버튼을 클릭한다.  |  |
|  | 2. 로그인 및 회원가입 화면으로 이동한다. |

## 4. 자전거 정보 등록

| Actor action(User) | System response |
| ------------ | --------------- |
|  | 1. 자전거 ID, 제품명을 입력하는 화면을 보여준다. |
| 2. 관리자는 자전거 ID, 제품명을 입력한다. 이후 등록 버튼을 클릭한다. |  |
|              | 3. 자전거 등록 완료 메세지를 출력한다. |

## 5. 자전거 대여

| Actor action(User) | System response |
| ------------ | --------------- |
| 1. 자전거 대여 버튼을 클릭한다. |                 |
|              | 2. 자전거 대여 완료 메세지를 출력한다. |

## 6. 자전거 대여 정보 조회

| Actor action(User) | System response |
| ------------ | --------------- |
| 1. 현재 대여 중인 자전거 정보 조회 버튼을 클릭한다. |                 |
|              | 2. 현재 대여 중인 자전거 리스트를 출력한다. 각 항목에는 자전거 ID, 제품명 정보가 출력된다. |
