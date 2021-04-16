# 00_EC2

## AWS 컴퓨팅 서비스
[AWS 컴퓨팅 서비스](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#1865bdc44f18494a921cfe67e1c40981)
## EC2
1. 인스턴스 유형 [링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#3fd909e2fe1e49fd9ec74a5c2b393cf9)
2. 키페어 생성 실습 [링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#89eb9d761f8b4094b216e4e0c80d1b9d)
3. Linux EC2 생성 실습 
- 인스턴스 생성 [링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#43ebf45366bd477f8de65529d566bb45)
- Amazon Linux 2에 Lamp 웹 서버 설치 [링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#fde53ad3083c47e6b07dfd27fe91f24a)

4. Linux EC2 연결 실습
- SSH 실습
    - SSH를 사용하여 Linux 인스턴스에 연결[링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#55ce840b537a424fb82d47f70ea0fa24)
    - PuTTY를 사용하여 Windows에서 Linux 인스턴스에 연결[링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#e2b5a7eedaf3496fb7c562a3dbfd790d)
    - 메타데이터 확인[링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#010dab43f1a84ba790f618e17f28c39c)
    - EC2 Instance Metadata Query Tool[링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#bf291525ff494179b408834f1688c391)
- EC2 Instance Connect 실습
    - EC2 Instance Connect 설정[링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#bf6306238c5543d4877542c2abde395b)
    - EC2 Instance Connect 연결[링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#bb5a4a765b70436287c3f7c4831efbd5)
    - 메타데이터와 사용자 데이터 확인
    ```
    curl http://169.254.169.254/latest/meta-data/
    ```
 5. Window EC2 인스턴스 생성 및 연결 실습[링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#5eeff75b5ee949cbb2ec73484aec04c3)


## EBS
1. EBS 볼륨 유형[링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#0ffaff4fac4d4ee08b4c968fdfb9ed30)
2. Linux EC2 인스턴스에 볼륨 생성, 볼륨 포맷 및 탑재 실습
- EBS 볼륨 생성[링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#ea747809d515493c90c7c8979a50dc60)

- EBS 볼륨을 인스턴스에 연결[링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#88959d4f387340f2ad7be1f47af9f524)

- 볼륨을 사용할 수 있도록 만들기[링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#c2aaa44e5893434ba3a9f27b806b3735)

3. Windows EC2 인스턴스 연결된 볼륨 포맷 및 탑재 실습[링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#8a2ec1823c73441194b8b93478891952)

4. 스냅샷 실습
- 스냅샷 생성[링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#a3cecf38665b422a829e745e1df525f1)
- 스냅샷에서 볼륨 생성[링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#e2f1b7a4ef1d40c8ae1efcbad1514ae7)

## 인스턴스 스토어
- 인스턴스 스토어 볼륨을 인스턴스에서 사용 가능하도록 만들기 실습[링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#2b935abc55944fb591d04ebaa6df6cfb)

## EFS
- Amazon EC2와 함께 Amazon EFS 사용 실습[링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#d9bdfdfebd2e486b84eee3a657f74d8e)

## FSx for Windows File Server
- Windos Server를 실행하는 EC2 인스턴스에 파일 공유 매핑 실습

1. 파일 시스템 생성[링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#c2442db4a4954ead81ef96f40ef86bb7)

2. Windos Server를 실행하는 EC2 인스턴스에 파일 공유 매핑[링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#259af7a26dc44a03b44e10679069be71)

3. 파일 공유에 데이터 쓰기[링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#62a7635433164bb0a276381a18d72148)

## AWS CLI
1. AWS CLI 참고 사이트
- 소개[링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#cf3d4ecdfb4c4ae0813332905dd77675)

- AWS CLI 설명서[링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#e676178631404c78888d0b627a571b45)

- AWS CLI References[링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#61bd9389266444778edf80c18906611b)

2. AWS CLI 구성 설정 우선 순위[링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#bb32f150e5384fffa710270aea39f97c)

3. AWS CLI 실습
- AWS CLI 설치 확인 [링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#2871cea96d50446c94de5270855163d8)
- AWS COnfigure를 통한 CLI 구성 [링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#beb82eea600d492ca597b59b620b910b)
- Amazon EC2의 IAM 역할 [링크](https://www.notion.so/Day-04-e23e635573964eb6b38dcab7c46a965e#2f70519ef1144cc8999aba2d0c21c0e3)
- 임시 자격 증명 확인