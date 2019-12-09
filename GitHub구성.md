# GitHub 계정 구성

1. Organization 구성
   1. 여러 team을 생성하여 team 별(그룹) 권한 관리
   2. **개인이 운영하던 환경을 organization으로 이관 시에 repository 저장소 위치 변경은 없다.**
      1. 다만, 기존 배포하던 과정에 새로운 인증 과정이 추가될 수 있다. (계정 마다 부여 받은 권한이 변경 될 수 있으므로..)
      2. **okimoki aws의 경우 jenkins에서 okimoki-master를 통해 인증 중이며, 해당 계정 사용하면 별도의 인증 변경을 필요 없을 것으로 보임.**

   3. 가격 정책
      1. https://github.com/pricing
      2. |Team                                   | Enterprise|
         |---------------------------------------|----------------------------|
         |**Unlimited public repositories**|=|
         |**Unlimited private repositories**|=|
         |**$9 per user / month**                    |**$21 per user / month**|
         |**10,000 total Action minutes/month**|**50,000 total Action minutes/month**|
         |2GB of GitHub Packages storage         | 50GB of GitHub Packages storage|
