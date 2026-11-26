---
title: Pendeck 개인정보처리방침 · Privacy Policy
permalink: /privacy/
---

# Pendeck 개인정보처리방침

시행일: 2026년 11월 26일

## 요약

Pendeck은 **iPad 안에서 동작하는(로컬 우선)** 학습 앱입니다. 문서·메모·필기·카드·문항·복습 기록은 **사용자의 iPad에**
저장됩니다. 1.0은 인터넷 없이 동작하고 계정 없이 시작합니다. 저희가 운영하는 서버는 AI 보조 요청을 전달하는 작은 중계 서버
하나뿐이며, 이 중계 프로그램은 전달하는 내용의 사본을 남기지 않습니다. 선택 기능 두 가지는 기본으로 꺼져 있습니다. **AI 보조**를 켜면 사용자가 요청할 때
공부하는 글의 일부가 이 중계 서버와 국내 게이트웨이 BizRouter를 거쳐 Anthropic의 Claude 모델로 전송됩니다(아래 'AI 기능'). **iCloud 동기화**를
켜면 사용자 본인의 iCloud에 사본을 두어 같은 계정의 다른 기기에서 이어 쓸 수 있습니다. 저희는 그 내용을 볼 수 없습니다(아래
'iCloud 동기화'). 내보낸 파일이나 문제 보고를 공유할지는 사용자가 정합니다. 사용자 본인의 기기 백업에도 앱 데이터가 들어갈 수 있습니다.

## 처리하는 정보

- **AI 보조나 iCloud 동기화를 켜지 않으면 앱이 스스로 보내는 것은 없습니다.** 분석·추적·광고 식별자를 쓰지 않고, 분석·광고 SDK도 없습니다.
  앱에 들어 있는 외부 패키지는 AI 보조만 쓰는 Anthropic의 공개 패키지 `ClaudeForFoundationModels`(Apache-2.0)를 고친
  사본 하나입니다. 앱에 든 개인정보 매니페스트(`Resources/PrivacyInfo.xcprivacy`)는 추적이 없다고 밝힙니다. AI 보조가
  공부하는 글을 Anthropic으로 보낼 수 있으므로, 매니페스트는 수집하는 데이터 유형 한 가지를 밝힙니다. '기타 사용자
  콘텐츠'(보내는 글)이며, 앱 기능을 위한 것이고 사용자와 연결되지 않으며 추적에 쓰지 않습니다. 앱은 기기 식별자를
  보내지 않습니다. 사용 사유를 밝혀야 하는 API는 세 가지이며 모두 기기 안에서만 씁니다.
  UserDefaults(`CA92.1`, 앱 자체 설정), 파일 시각(`C617.1`, 앱 자체 파일, `3B52.1`, 복원하려고 고른 백업 파일), 디스크
  공간(`E174.1`, 백업을 쓰기 전 남은 공간 확인, `85F4.1`, 백업이 들어가지 않을 때 남은 공간 표시). iCloud 동기화의 자료는
  사용자 본인의 iCloud 계정에 저장되며 저희는 접근할 수 없습니다. 저희가 수집하는 정보가 아니므로 개인정보 매니페스트와
  App Store 표시는 바뀌지 않습니다.
- **iPad에 두는 것:** 가져온 PDF·이미지·Anki 덱·노트, 필기와 가림, 그것으로 만든 카드와 복습 일정, PDF로 만든
  문항과 그 문항에 쓴 답, 쪽 북마크, '최근 삭제'에 있는 자료(이것도 백업 zip에 들어갑니다). 사용자가 *직접* 파일을
  내보내거나 공유할 때, iOS가 사용자 본인의 iCloud·컴퓨터 백업에 넣을 때, 사용자가 iCloud 동기화를 켰을 때만(아래
  'iCloud 동기화') iPad 밖으로 나갑니다. 예외는 AI 보조 하나입니다. 켜 두면 'AI 기능'에 적은 글이 사용자가 요청할 때 전송됩니다.
- **최근 삭제:** 자료를 지우면 필기·카드·문항·복습 기록과 함께 '최근 삭제'로 옮겨집니다. 그곳에서 복원하거나 영구
  삭제할 수 있습니다. 지운 날로부터 30일이 지나면, 그다음 앱을 열 때 앱이 영구 삭제합니다.
- **필기 검색:** 검색에서 필기를 찾을 수 있도록 앱이 iPad 안에서 필기를 글자로 읽습니다(한국어·영어). 이 글자는 iPad의
  별도 파일에 두며, 백업 zip과 iOS 기기 백업에는 들어가지 않고, 필요하면 앱이 다시 만듭니다. '모든 데이터 삭제'로
  지워지며 어디로도 보내지 않습니다(AI 보조도 보내지 않습니다. '보내지 않는 것' 참고).
- **암호가 걸린 PDF:** 열 때 암호가 필요한 PDF를 가져오면 앱이 암호를 물어 파일을 연 뒤, 암호 *없는* 사본을 iPad의 앱
  저장소에 둡니다. 원본의 암호 보호와 복사·인쇄 제한은 이 사본에 적용되지 않습니다. 입력한 암호는 저장하거나 기록하지
  않고 iPad 밖으로 보내지 않습니다.
- **카메라(문서 스캔):** 쪽을 스캔하는 동안에만 씁니다. 스캔 결과는 앱 안의 PDF가 되고 사진 보관함에 저장하지 않습니다.
- **사진(쪽에 넣는 이미지):** 앱은 사진 보관함에 접근하지 않으며 다른 사진을 볼 수 없습니다. 이미지를 넣을 때 시스템
  사진 선택기가 사용자가 고른 사진만 앱에 넘겨 줍니다. 앱은 메타데이터(위치·기기·촬영 시각)를 뺀 축소본을 iPad의 앱
  저장소에 두고, 사진 보관함에 아무것도 저장하지 않으며, 사진을 iPad 밖으로 보내지 않습니다. 다른 내용과 마찬가지로
  사용자가 만든 내보내기나 백업에 들어갈 때만 iPad 밖으로 나갑니다.
- **공유 확장:** 다른 앱에서 이 앱으로 공유한 파일은 iPad의 앱 저장소로 복사되고, 다음에 앱을 열 때 가져옵니다.
- **복습 알림(선택, 기본 꺼짐):** 설정에서 켤 때 알림 권한을 묻고(처음 실행할 때는 묻지 않습니다), 매일 알림을 최대
  7일 치까지 iPad 안에서 예약합니다. 알림에는 복습할 카드 수만 나오고 카드·자료·과목 이름은 나오지 않습니다. 복습
  알림은 푸시 서버와 기기 토큰을 쓰지 않아 알림에 관한 정보는 iPad 밖으로 나가지 않습니다.
- **사용 기록:** 최근 앱 이벤트 목록(이벤트 이름·시각·숫자. 예를 들어 '이 PDF로 문제 풀기'가 문항을 몇 개 만들었고
  얼마나 걸렸는지. 제목·파일 이름·쪽 번호·필기·카드나 문항 내용은 넣지 않습니다)을 iPad의 파일 하나에 둡니다. 최근
  4주의 이벤트 가운데 최신 2,000개입니다. 앱을 꺼도 남습니다. 사용자가 *직접* 문제 보고를 보낼 때만 보고에 들어갑니다
  (최근 50개와, 남아 있는 이벤트에서 뽑은 '문맥 넓히기'·AI 보조의 횟수와 걸린 시간). 기본으로 켜져 있고, 설정 → 피드백
  → '사용 기록 넣기'를 끄면 파일도 지워집니다. 다른 앱 데이터처럼 사용자 본인의 기기 백업에 들어갈 수 있으며, 앱의 백업
  zip에는 들어가지 않습니다.
- **문제 보고:** 사용자가 메일이나 공유 시트로 직접 보냅니다. 보고에는 앱·iOS 버전과 빌드, 기기 모델, 언어·지역·글자
  크기 설정, 최근 사용 기록 이벤트 최대 50개, '문맥 넓히기'·AI 보조의 4주 횟수(실패 이유별 포함)와 걸린 시간, 사용자가
  쓴 메모, 그때 화면의 캡처가 들어갑니다. 캡처는 기본으로 켜져 있으며, 보고 화면에서 '스크린샷 넣기'를 끄면 빠집니다.
  보내기 전에 그 화면에서 미리 볼 수 있습니다. 앱이 스스로 보내지 않습니다. 메일로 보내면 저희는 보낸 사람의 이메일 주소와
  보고 내용(첨부 포함)을 받습니다. 답장과 문제 해결에만 쓰고, 해결된 뒤 1년 안에 지우며, 요청하면 바로 지웁니다.

## iCloud 동기화

**iCloud 동기화**는 선택 기능이며 **기본으로 꺼져 있습니다**. 설정·백업 → 'iCloud 동기화'에서 켜고 끄며, 바꾼 설정은 다음에 앱을 열 때 적용됩니다.

- **저장 위치:** **사용자 본인의 iCloud 계정** 안에 있는 이 앱 전용 비공개 데이터베이스(Apple CloudKit). 같은 iCloud 계정으로
  로그인한 기기만 읽을 수 있습니다. 개발자인 저희는 보거나 읽거나 받을 수 없습니다. Apple의 iCloud 약관과 개인정보
  처리방침이 적용됩니다. iCloud 서버는 Apple이 운영하며 대한민국 밖에 있을 수 있습니다. 개발자는 이 자료에 접근할 수 없습니다.
- **동기화하는 것:** 자료(PDF·이미지), 필기, 가림, 쪽의 글상자와 이미지, 카드와 카드 이미지, 문항, 복습 기록, 최근 삭제, 쪽
  북마크. 한 기기에서 자료를 지우거나 되살리면 다른 기기에서도 그렇게 됩니다.
- **동기화하지 않는 것:** 앱 설정(AI 보조 스위치와 동의 포함), 사용 기록, AI 사례 기록, 필기 검색 색인(기기마다 새로 만듭니다).
- **계정:** Pendeck에는 여전히 계정이 없고 계정 없이 시작합니다. iCloud 동기화에는 iPad의 iCloud 로그인이 필요합니다.
  로그인하지 않았거나 인터넷이 없어도 iPad의 자료로 계속 쓸 수 있습니다.
- **끄기:** 스위치를 끕니다. 다음에 앱을 열 때부터 더 동기화하지 않으며, 이 iPad의 자료와 iCloud의 사본은 둘 다 남습니다.
- **iCloud에서 로그아웃할 때:** iCloud에서 로그아웃하거나 iPad 설정에서 Pendeck의 iCloud 사용을 끄면, 동기화된 자료가 이
  iPad에서 사라집니다. iCloud의 사본은 남아 있어 같은 계정으로 다시 로그인하고 앱을 열면 돌아오지만, 아직 올라가지 않은
  변경은 잃을 수 있습니다. 동기화를 멈추고 이 iPad의 자료를 그대로 두려면 앱 안의 스위치를 끄고, 로그아웃하기 전에 백업을
  만들어 두세요.
- **iCloud에서 지우기:** 앱은 iCloud의 사본을 지우지 않습니다. 동기화한 iPad의 '모든 데이터 삭제'는 '이 기기의 데이터만
  지우기'를 보이며 iCloud 사본은 남깁니다. 그 사본을 지우려면 먼저 모든 기기에서 iCloud 동기화를 끈 뒤, iPad 설정 →
  사용자 이름 → iCloud → 저장 공간 관리 → Pendeck에서 지웁니다.
- **백업을 복원하면** 그 iPad의 iCloud 동기화가 꺼집니다. 다시 켜면 복원한 데이터가 iCloud의 사본과 합쳐집니다.

## AI 기능

**AI 보조**는 선택 기능이며 **기본으로 꺼져 있습니다**. 스위치는 iPadOS 27 이상에서만 설정에 보입니다. 꺼져 있거나
네트워크가 없으면 앱은 AI 없이 그대로 동작합니다.

- **하는 일:** 복습에서 카드의 '문맥 넓히기'를 처음 누를 때, 앱이 미리 만든 넓은 문맥 범위 가운데 무엇을 보여 줄지
  Claude가 고릅니다. Claude가 돌려주는 것은 범위의 이름 하나이며, 모델이 쓴 글은 화면에 나오거나 카드에 저장되지
  않습니다. 요청이 실패하거나 3초 넘게 걸리면 AI 없이 할 때처럼 문맥을 한 단계 넓힙니다. '이 PDF로 문제 풀기'에서
  AI로 문항을 만들면, 사용자가 고른 쪽으로 Claude가 문항(정답·해설·인용한 근거 포함)을 씁니다. 문항이 인용한 구절이
  그 쪽에 있는지 확인한 뒤 문항을 iPad의 앱 문제은행에 둡니다.
- **요청을 처리하는 곳과 목적:** 요청은 '문맥 넓히기'가 보여 줄 문맥 범위를 고르고, 사용자가 고른 쪽의 글로 문항을 쓰는
  데만 씁니다. 요청은 차례로 세 곳을 거칩니다.
  1. **저희 중계 서버:** 개발자가 Cloudflare Workers에 올린 작은 프로그램입니다(Cloudflare, Inc., 미국, 개인정보 문의
     dpo@cloudflare.com). 앱에 API 키를 넣지 않도록 키를 보관합니다. 요청의 경로, 앱에 든 고정 값(아래), 허용한 Claude
     모델인지, 출력 길이 상한, 요청 크기만 검사하고 글과 지시문은 바꾸지 않고 전달합니다. 저희 중계 프로그램은 글·응답과
     앱 정보를 저장하거나 기록하지 않습니다. IP 주소는 남용을 막기 위해 1분 동안의 요청 수를 세는 데만 Cloudflare의 요청 수
     제한 기능이 잠깐 쓰며, 저희는 이를 저장하거나 기록하지 않습니다.
  2. **BizRouter:** 대한민국의 LLM API 게이트웨이이며 주식회사 AI3(서울 강남구 영동대로85길 34, 개인정보 문의
     privacy@ai3.kr)가 운영합니다. 게이트웨이와 기록은 서울(AWS)에 있습니다.
  3. **Claude를 실행하는 곳:** Anthropic, PBC의 모델입니다. BizRouter는 요청을 **Anthropic, PBC**의 Claude API(미국,
     개인정보 문의 privacy@anthropic.com)나 **Amazon Web Services, Inc.**(AWS, 미국)의 **Amazon Bedrock**을 통해 보냅니다.

  저희는 Anthropic의 Claude 모델만 요청합니다.
- **AI 보조를 켠 채 '문맥 넓히기'를 누를 때 보내는 것:** 앱이 그 카드의 쪽에서 잘라 낸 후보 범위들의 글(몇 줄부터 쪽
  전체 글까지)을 한 요청에 모두 보내므로, 요청마다 그 쪽의 글 전체가 들어갑니다(정답과 쪽에 다시 나오는 정답은 가린
  채). 또 가린 정답의 글자와 고정된 지시문을 보냅니다. 요청마다 앱 식별자(번들 ID), 앱 버전, iPadOS 버전(패키지의
  User-Agent로, 패키지 자체 버전과 Swift 버전 포함), 그리고 앱에 든 고정 값이 함께 갑니다. 고정 값은 모든 설치가 같아
  사용자나 iPad가 아니라 앱을 가리킵니다. 다른 인터넷 연결과 마찬가지로 요청은 사용자의 IP 주소에서 나갑니다. IP 주소,
  User-Agent, 고정 값은 저희 중계 서버가 받고 어디로도 넘기지 않습니다. BizRouter와 Claude를 실행하는 곳(Anthropic 또는 AWS)은 글, 지시문, 모델 설정을 받습니다.
- **AI로 문항을 만들 때 보내는 것:** 요청마다 사용자가 고른 쪽의 글(줄마다 글, 쪽 번호와 쪽 안의 위치, 그 줄에
  가림·강조·필기·다른 표시가 있는지 나타내는 숫자), 그 쪽의 메모와 글상자의 글(다른 앱이 PDF에 남긴 메모 포함), 같은
  실행에서 이미 만든 문항 최대 12개의 질문(겹치지 않게), 문항 유형·개수·목표 점수, 고정된 지시문을 보냅니다. 여기서는 가린 정답을
  **가리지 않습니다**. 사용자가 뺀 영역과 용어는 빠집니다. 무엇이든 보내기 전에 앱이 보낼 쪽과 글을 보여 주고 확인을
  받습니다. 요청마다 위와 같은 앱 정보, 고정 값, IP 주소가 함께 갑니다.
- **보내지 않는 것:** 쪽 이미지, 필기, 앱이 iPad 안에서 필기를 읽은 글자, 자료·파일 이름, 계정 정보(앱에 계정이
  없습니다), 기기 식별자와 접근 토큰. 다른 노트 앱에서 내보낸 PDF처럼 필기가 이미 PDF의 글에 들어 있으면, 그 글은 그 쪽의 다른 글과 함께
  전송됩니다. '문맥 넓히기'는 그 카드의 쪽만, 문항 만들기는 사용자가 고른 쪽만 보냅니다.
- **국외 이전:** 보낼 때마다 암호화된 연결(HTTPS)로 전송됩니다. 저희 중계 서버는 요청을 받은 Cloudflare 데이터센터에서
  실행되며, 그 데이터센터는 대한민국 밖일 수 있습니다. BizRouter는 서울에서 요청을 처리한 뒤 글과 지시문을 Anthropic의
  API나 Amazon Bedrock(AWS)을 통해 Claude로 보내고, 어느 쪽이든 미국이나 다른 나라에서 처리할 수 있습니다. 대한민국 안에서만
  처리된다는 보장은 없습니다.
- **동의:** 스위치를 처음 켤 때 앱은 요청을 처리하는 곳(저희 중계 서버, BizRouter, Anthropic의 API 또는 Amazon Bedrock)과 목적, 보내는 것과
  보내지 않는 것, 국외 이전과 BizRouter·Anthropic이 보관하는 것(굵게), 주의 사항, 거부하거나 끄는 법,
  개인정보처리방침을 한 화면에 보여 줍니다. '만 14세 이상입니다'를 확인한 뒤에만 '동의하고 켜기'가 동작하고, '취소'를
  누르면 꺼진 채로 둡니다. 동의하기 전에는 아무것도 보내지 않습니다. 앱은 사용자가 동의한 화면의 판을 기록합니다. 화면
  내용이 실질적으로 바뀌면 스위치가 꺼진 것으로 보이고, 아무것도 보내지 않으며, 켜려면 다시 묻습니다. 같은 동의가 '문맥 넓히기'와 문항 만들기에 함께
  적용되며, 문항 만들기는 보낼 때마다 한 번 더 묻습니다. 설정 → AI 보조 → '보내는 내용 다시 보기'에서 같은 화면을
  언제든 다시 볼 수 있습니다.
- **거부:** 동의하지 않거나 끄면 다른 기능은 모두 이전처럼 동작합니다. '문맥 넓히기'는 AI 없이 한 단계씩 넓어지고,
  문항은 기기 안의 로컬 생성으로 AI 없이 만들 수 있습니다. 끄면 다음 요청부터 보내지 않습니다.
- **보내기 전 확인:** '문맥 넓히기'는 정답만 가리고, 문항 만들기는 아무것도 가리지 않습니다. 앱은 그 밖의 내용을 걸러
  내지 않습니다. 다른 사람의 이름이나 연락처, 식별할 수 있는 환자 정보, 주민등록번호가 들어 있는 자료에서는 AI 보조를
  끄세요.
- **아동:** AI 보조는 만 14세 이상 사용자를 위한 기능이며, 동의 화면에서 이를 확인합니다.
- **하루 한도:** '문맥 넓히기' 요청은 기기마다 하루 50번까지이며, 넘으면 '문맥 넓히기'는 AI 없이 동작합니다. 문항
  만들기는 따로 셉니다. 기기마다 하루 12번까지 요청하며(요청 한 번에 문항 최대 5개), 넘으면 나머지는 다음 날까지
  기다립니다. 둘 다 iPad 안에서 셉니다. 저희 중계 서버가 쓰는 BizRouter 키에는 모든 AI 요청의 하루 총액 한도도 있어,
  닿으면 앱은 '거부'에 적은 것처럼 AI 없이 동작합니다.
- **저희 중계 서버가 보관하는 것:** 없습니다. 저희 중계 프로그램은 요청과 응답을 전달할 뿐 이를 저장하거나 기록하지
  않으며, IP 주소와 앱 정보도 저장하거나 기록하지 않습니다. IP 주소는 1분 동안의 요청 수를 세는 데만 씁니다(위 참고).
- **BizRouter가 보관하는 것:** 저희는 BizRouter의 「감사 로그 저장」을 꺼 두었습니다. BizRouter는 이 설정을 끄면 요청과
  응답의 본문을 저장하지 않고, 정산 근거인 과금 기록(시각, 모델, 토큰 수, 요금, 처리 결과 등)을 보관하며 그 기간은 밝히지
  않았고, 재시도·폴백 같은 요청 처리 과정 기록은 90일 보관한다고 밝히고 있습니다. 이용약관은 오류 확인을 위한 일시적
  기록을 최대 30일, 법령이 요구하는 기록을 보관할 수 있다고 정합니다
  ([데이터 정책](https://bizrouter.ai/docs/data-policy), [이용약관](https://bizrouter.ai/terms),
  [개인정보처리방침](https://bizrouter.ai/privacy)). BizRouter는 제공사 API를 부를 때 학습 허용이나 데이터 공유 옵션을
  켜지 않는다고 밝히고 있습니다.
- **Anthropic이 보관하는 것(BizRouter가 Anthropic의 API를 쓸 때):** Anthropic은 API 입력과 출력을 기본적으로 30일 안에 삭제한다고 밝히고 있습니다. 보관
  기간이 더 긴 서비스, 별도 계약, 이용 정책 집행이나 법적 요구가 있으면 이 기간이 달라질 수 있습니다. 자동 안전
  시스템이 표시한 요청은 입력과 출력을 최대 2년, 분류 점수를 최대 7년 보관할 수 있습니다. Anthropic은 보관한 데이터를
  명시적 허락 없이 모델 학습에 쓰지 않는다고 밝히고 있습니다
  ([보관 정책](https://privacy.claude.com/en/articles/7996866-how-long-do-you-store-my-organization-s-data),
  [API 데이터 보관](https://platform.claude.com/docs/en/manage-claude/api-and-data-retention)).
  BizRouter의 데이터 정책도 Anthropic이 입력과 출력을 받거나 만든 뒤 30일 안에 삭제한다고(정책 위반으로 표시되면 최대
  2년) 적고 있습니다. 저희 중계 서버는 요청을 받아 전달할 뿐 사본을 보관하지 않습니다.
- **BizRouter가 Amazon Bedrock을 쓸 때:** 요청은 위 Anthropic의 보관 정책이 아니라 AWS의 Amazon Bedrock 정책에 따라
  처리됩니다.
- **사례 기록(선택, 기본 꺼짐):** 설정 → AI 보조 → '사례 기록 남기기'를 켜면, '문맥 넓히기' AI 요청마다(문항 만들기는
  제외) 보낸 글, 가린 정답, 앱이 고른 범위, Claude가 고른 범위, 모델 설정과 걸린 시간을 iPad의 파일 하나에 둡니다(최신
  1,000개). 이 파일에는 자료 이름·쪽 번호·식별자·시각이 없습니다. 앱은 이 파일을 어디로도 보내지 않으며, 사용자가 공유
  시트로 직접 내보내거나 iPadOS가 사용자 본인의 iCloud·컴퓨터 백업에 넣을 때만 iPad 밖으로 나갑니다(앱의 백업 zip에는
  들어가지 않습니다). 설정에서 지울 수 있고, '모든 데이터 삭제'로도 지워집니다.
- **제3자의 보호 수준:** AI 보조 요청을 처리하는 곳(Cloudflare, Inc., BizRouter 운영사 주식회사 AI3, Anthropic, PBC, Amazon Bedrock을 쓸 때의
  Amazon Web Services, Inc.)은 이
  방침에 적은 것과 같거나 그와 동등한 수준으로 사용자 데이터를 보호합니다. 각 곳은 위에 적은 목적으로만 데이터를 처리하고,
  위에 적은 대로만 보관합니다.

## 개인정보 처리 위탁과 국외 이전
AI 보조를 켠 경우에만 해당합니다. AI 보조를 켜지 않으면 위탁하거나 국외로 이전하는 정보가 없습니다. iCloud 동기화는 사용자
본인의 iCloud 계정에 저장하는 것이며, 저희가 위탁하거나 국외로 이전하는 정보가 아닙니다(위 'iCloud 동기화').

**처리 위탁.** AI 보조 요청을 전달하고 처리하는 일을 아래에 맡깁니다.

| 수탁자 | 맡기는 일 |
|---|---|
| Cloudflare, Inc. (미국, 개인정보 문의: dpo@cloudflare.com) | 저희 중계 서버(Cloudflare Workers)의 실행: AI 요청을 받아 BizRouter로 전달 |
| 주식회사 AI3 (BizRouter 운영사, 서울 강남구 영동대로85길 34, 개인정보 문의: privacy@ai3.kr) | AI 요청을 Claude(Anthropic API 또는 Amazon Bedrock)로 전달하는 게이트웨이(서울, AWS) |
| Anthropic, PBC (미국, 개인정보 문의: privacy@anthropic.com) — 주식회사 AI3가 다시 맡김(Anthropic API를 쓸 때) | Claude로 요청을 처리해 응답 만들기 |
| Amazon Web Services, Inc. (미국, Amazon Bedrock) — 주식회사 AI3가 다시 맡김(Amazon Bedrock을 쓸 때) | Claude로 요청을 처리해 응답 만들기 |

**국외 이전.**

| 항목 | Cloudflare, Inc. (저희 중계 서버) | Anthropic, PBC 또는 Amazon Web Services, Inc.(Amazon Bedrock) |
|---|---|---|
| 이전되는 국가 | 요청을 받은 Cloudflare 데이터센터가 있는 나라(대한민국 밖일 수 있음). 회사 소재지는 미국 | 미국과 그 밖의 나라(대한민국 안 처리 보장 없음) |
| 이전 시기와 방법 | AI 보조를 켠 상태에서 '문맥 넓히기'를 누르거나 AI로 문항을 만들 때마다 암호화된 연결(HTTPS)로 전송 | 같은 때, BizRouter(서울)를 거쳐 암호화된 연결(HTTPS)로 전송 |
| 이전되는 항목 | 위 'AI 기능'의 보내는 것: '문맥 넓히기'의 후보 범위 글(그 쪽의 글 전체, 정답은 가린 채)과 가린 정답의 글자, 문항 만들기의 고른 쪽 글·메모·글상자 글·이미 만든 문항·문항 유형과 개수와 목표 점수, 고정된 지시문, 모델 설정, 앱 식별자·앱 버전·iPadOS 버전(User-Agent), 앱에 든 고정 값, IP 주소 | 왼쪽 항목 가운데 글, 지시문, 모델 설정(IP 주소, User-Agent, 고정 값은 넘기지 않음) |
| 이용 목적 | 요청을 BizRouter로 전달 | '문맥 넓히기'가 보여 줄 문맥 범위 고르기, 고른 쪽의 글로 문항 쓰기 |
| 보유·이용 기간 | 보관하지 않음(전달하는 동안만 처리, IP 주소는 1분 동안의 요청 수 제한에만 잠깐 씀) | Anthropic API를 거치면 Anthropic 정책에 따라 API 입력과 출력은 기본적으로 30일 안에 삭제(보관 기간이 더 긴 서비스, 별도 계약, 이용 정책 집행이나 법적 요구가 있으면 달라질 수 있고, 자동 안전 시스템이 표시한 요청은 입력과 출력을 최대 2년, 분류 점수를 최대 7년 보관). Amazon Bedrock을 거치면 AWS의 Amazon Bedrock 정책에 따름 |
| 거부 방법과 효과 | AI 보조를 켜지 않거나 설정에서 끄면 다음 요청부터 전송하지 않습니다. 거부해도 다른 기능은 모두 그대로 쓸 수 있고, '문맥 넓히기'는 AI 없이 한 단계씩 넓어지며, 문항은 로컬 생성으로 만들 수 있습니다 | 왼쪽과 같음 |

BizRouter(주식회사 AI3)는 국내에서 처리하며, 저희가 끈 「감사 로그 저장」 설정에서는 본문을 저장하지 않는다고 밝히고
있습니다. 과금 기록과 처리 과정 기록의 보관은 위 'BizRouter가 보관하는 것'을 보세요.

## 사용자가 할 수 있는 것

- **백업:** 설정·백업의 '백업 내보내기'를 누르면 자료·필기·카드·문항·복습 기록을 zip으로 만듭니다. zip에는 암호가
  없고, 가져온 암호 PDF의 암호 없는 사본을 포함해 iPad에 저장된 파일이 그대로 들어 있습니다. 나만 쓰는 곳에
  보관하세요. iCloud·컴퓨터 백업으로 iPad를 복원해도 앱 데이터가 돌아옵니다.
- **복원:** 설정·백업에서 '백업에서 복원'으로 앱 백업 zip을 고르고 '복원 예약'을 누릅니다. 앱을 종료했다가 다시 열면
  iPad의 학습 데이터를 바꿉니다. 앱 설정은 그대로 둡니다. Pendeck은 이전 데이터를 이 iPad에 보관하되 기기 백업에는 넣지
  않습니다. '이전 데이터로 되돌리기'를 누르고 앱을 종료했다가 다시 열면 두 데이터를 맞바꿉니다. '이전 데이터 삭제'와 '모든
  데이터 삭제'는 보관한 사본을 지웁니다. 다른 zip을 복원하면 보관한 사본은 그 복원 직전의 데이터로 바뀝니다.
- **내보내기:** '데이터 내보내기 (JSON)'는 다른 도구도 읽을 수 있는 개방형 형식입니다. 카드는 CSV로 내보내고, 문서는
  필기·글상자·이미지가 들어간 PDF(모든 쪽, 이 쪽만, 쪽 범위)나 필기 없는 원본 PDF로 내보냅니다.
- **AI 보조:** 설정 → AI 보조의 스위치를 끄면 다음 요청부터 아무것도 보내지 않습니다. '모든 데이터 삭제'를 하면 동의
  기록도 지워져, 다음에 켤 때 다시 묻습니다.
- **이미 보낸 AI 요청:** 앱은 요청에 사용자나 기기를 알아볼 식별자를 넣지 않으므로 저희와 BizRouter·Anthropic·AWS는 특정
  사용자의 요청을 찾아 지울 수 없습니다. 보낸 글은 위 'BizRouter가 보관하는 것'·'Anthropic이 보관하는 것'에 적은 기간이
  지나면(Amazon Bedrock을 거쳤다면 AWS의 정책에 따라) 지워집니다. 삭제나 동의 철회에 관해 궁금한 점은 pendeck.support@gmail.com으로 보내 주세요.
- **알림:** 설정 → 복습 일정 → '복습 알림'을 끄면 예약된 알림도 지워집니다. iOS 설정 → 알림에서도 앱의 알림을 끌 수
  있습니다.
- **자료 삭제:** 지운 자료는 사이드바의 '최근 삭제'로 옮겨집니다. 그곳에서 '영구 삭제'나 '모두 비우기'를 누르면 바로
  iPad에서 지워지고, 그러지 않으면 30일 뒤에 지워집니다(위 참고).
- **모두 삭제:** 설정 → 데이터 삭제 → '모든 데이터 삭제'를 누르면 앱이 이 iPad에 저장한 모든 것이 되돌릴 수 없게
  지워집니다. 예약된 복습 알림, 복원 중인 백업, 복원하기 전에 보관한 데이터도 함께 지워집니다. 앱을 삭제해도 이 iPad에서는
  모두 지워집니다. 이미 내보낸 파일, 기기 백업, AI 보조로 이미 보낸 요청에는 미치지 않습니다. iCloud 동기화를 쓴 iPad에서는
  이 버튼이 '이 기기의 데이터만 지우기'이며, 다음에 앱을 열 때 이 iPad의 데이터를 지우고 iCloud의 사본은 남깁니다(위
  'iCloud 동기화').

## 의료기기가 아닙니다

Pendeck은 **학습 보조 도구**이며 진단·치료·처방에 쓰는 도구가 아닙니다. 환자 진료에 이 앱의 내용을 근거로 삼지
마십시오.

## 개인정보 보호책임자
손창현 · 이메일 pendeck.support@gmail.com

## 문의

이메일: pendeck.support@gmail.com · 지원 페이지: https://changyoungduo.github.io/pendeck-support/ — 질문과 문제 보고는 이
주소로 받습니다(지원 페이지에 있는 GitHub 이슈로도 받습니다).

## 방침 변경
이 방침이 바뀌면 이 페이지에 새 시행일과 함께 알립니다.

---

# Pendeck Privacy Policy

Effective: November 26, 2026

## Summary

This is a **local-first** study app. Your documents, notes, handwriting, cards, questions and review
history are stored **on your iPad**. Version 1.0 works offline and needs no account to start. The only server we run is a small
relay program for AI Assist that keeps no copy of what it passes on. Two optional features are off by default. If you turn on **AI Assist**,
part of the text you study is sent, through that relay and the Korean gateway BizRouter, to Anthropic's Claude models
when you ask for it (see "AI features"). If you turn on **iCloud Sync**, a copy is kept in your own iCloud so your other devices
signed in to it can use it; we cannot see it (see "iCloud Sync"). You choose when to share an export or problem report.
Your own device backup may also include app data.

## What we collect

- **The app sends nothing on its own unless you turn on AI Assist or iCloud Sync.** There is no analytics, no tracking, no advertising identifier
  and no analytics or advertising SDK. The app includes one third-party package, a modified copy of Anthropic's
  open-source `ClaudeForFoundationModels` (Apache-2.0), used only by AI Assist. The bundled privacy manifest
  (`Resources/PrivacyInfo.xcprivacy`) declares no tracking. Because AI Assist can send text you study to
  Anthropic, it declares one collected data type, "Other User Content" (the text sent), for app functionality,
  not linked to you and not used for tracking. The app sends no device identifier. It declares three required-reason APIs, all used only on the device:
  UserDefaults (`CA92.1`, the app's own settings), file timestamps (`C617.1`, the app's own files;
  `3B52.1`, a backup file you pick to restore) and disk space (`E174.1`, checking free space before
  writing a backup; `85F4.1`, showing how much space is free when a backup does not fit). iCloud Sync stores your
  data in your own iCloud account, which we cannot access; it is not data we collect and does not change the privacy
  manifest or the App Store label.
- **Kept on your iPad:** the PDFs, images, Anki decks and notes you import, your handwriting and
  masks, the cards made from them and their review schedule, the questions made from your PDFs and
  your answers to them, your page bookmarks, and materials in Recently Deleted (also part of the backup zip).
  They leave the iPad only when *you* export or share a file, when iOS includes them in your own iCloud or
  computer backup, or when you turn on iCloud Sync (see "iCloud Sync"). The one exception is AI Assist: if you turn
  it on, the text described under "AI features" is sent when you ask for it.
- **Recently Deleted:** a material you delete moves to Recently Deleted with its handwriting, cards, questions
  and review history. You can restore it or delete it permanently there. Thirty days after you deleted it, the
  app deletes it permanently the next time it opens.
- **Handwriting search:** to find your handwriting in search, the app reads it into text on the iPad
  (Korean and English). That text is kept in a separate file on the iPad that is not in the backup zip or in
  iOS device backups; the app builds it again when needed. "Delete all data" deletes it, and it is never sent
  anywhere (AI Assist does not send it either; see "Not sent").
- **Password-protected PDFs:** when you import a PDF that needs a password to open, the app asks for it,
  opens the file, and keeps a copy *without* the password in its own storage on the iPad; the original's
  password protection and any copy or print restrictions do not apply to that copy. The password you type
  is not saved or logged and never leaves the iPad.
- **Camera (document scan):** used only while you scan pages. The scan becomes a PDF in the app and
  is not saved to your photo library.
- **Photos (images on a page):** the app has no access to your photo library and cannot see your other
  photos. When you insert an image, the system photo picker hands the app only the photo you chose. The
  app keeps a reduced copy without its metadata (location, device, capture time) in its own storage on the
  iPad, never saves anything to your photo library, and never sends the photo off the iPad; like your other
  content, it leaves the iPad only in an export or backup you make.
- **Share extension:** files you share to the app from another app are copied into the app's own
  storage on the iPad and imported the next time the app opens.
- **Review reminders (optional, off by default):** if you turn them on in Settings, the app asks for
  notification permission then — never at first launch — and schedules up to seven daily reminders on
  the iPad itself. A reminder shows only how many cards wait for review, never a card, material or
  subject name. Reminders use no push server and no device token, so nothing about reminders leaves the iPad.
- **Usage log:** a list of recent app events (event names, times and numbers, such as how many questions
  "Practice with this PDF" made and how long that took; no titles, file names, page numbers, handwriting, card or
  question text) is kept in one file on the iPad: the newest 2,000 events of the last four
  weeks. It survives quitting the app. It goes into a problem report only when *you* send that report
  (the 50 most recent events, plus counts and timings about "Widen context" and AI Assist taken from the
  kept events). On by default; Settings → Feedback → "Include usage log" turns it off and deletes the
  file. Like your other app data it may be part of your own device backup; it is not in the app's backup zip.
- **Problem reports:** you send them yourself, by mail or through the share sheet. A report holds the
  app and iOS versions and build, the device model, language, region and text size settings, up to 50
  recent usage-log events, four-week counts (including by failure reason) and timings for "Widen context"
  and AI Assist, your note, and a screenshot of the screen as it was. The screenshot is on by default: turn off
  "Include screenshot" on the report screen to leave it out, and check the preview there before sending. The app
  never sends one on its own. If you send it by email, we receive your email address and the report, including
  attachments. We use them only to reply and fix the problem, delete them within one year after the issue is
  resolved, and delete them sooner on request.

## iCloud Sync

**iCloud Sync** is optional and **off by default**. Settings & Backup → "iCloud Sync" turns it on or off; the
change applies the next time you open the app.

- **Where it goes:** a private database for this app in **your own iCloud account** (Apple's CloudKit). Only
  devices signed in to the same iCloud account can read it. We, the developer, cannot see, read or receive it.
  Apple's iCloud terms and privacy policy apply to it. Apple runs the iCloud servers, which may be outside the
  Republic of Korea, and the developer cannot access this data.
- **What syncs:** your materials (PDFs and images), handwriting, masks, text boxes and images on pages, cards and
  their images, questions, review history, Recently Deleted and page bookmarks. Deleting or restoring a material on
  one device does the same on the others.
- **What does not:** app settings (including the AI Assist switch and consent), the usage log, AI case
  records and the handwriting search index (each device builds its own).
- **Account:** Pendeck still has no account and needs none to start. iCloud Sync needs the iPad to be signed
  in to iCloud. Without that, or without a network, the app keeps working with the data on the iPad.
- **Turning it off:** turn the switch off. From the next time you open the app nothing more is synced; the data
  on this iPad and the copy in iCloud both stay.
- **Signing out of iCloud:** if you sign out of iCloud, or turn off iCloud for Pendeck in the iPad's Settings,
  the synced data is removed from this iPad. The copy in iCloud stays and comes back when you sign in to the same
  account and open the app again; changes not yet uploaded can be lost. To stop syncing and keep the data on this
  iPad, turn off the app's own switch instead, and make a backup before signing out.
- **Deleting it from iCloud:** the app does not delete the copy in iCloud. On an iPad that has synced,
  "Delete all data" offers "Erase Only This Device", which leaves the copy in iCloud. To delete that copy, first turn
  off iCloud Sync on every device, then use the iPad's Settings → your name → iCloud → Manage Storage → Pendeck.
- **Restoring a backup** turns iCloud Sync off on that iPad. Turning it back on merges the restored data with
  the copy in iCloud.

## AI features

**AI Assist** is optional and **off by default**. Its switch appears in Settings only on iPadOS 27 or later.
With it off, or without a network, the rest of the app works the same, without AI.

- **What it does:** in review, the first time you tap "Widen context" on a card, Claude picks which of the
  wider context ranges the app prepared should be shown. Claude's output is one label; no text written by
  the model is shown or stored in a card. If the request fails or takes longer than three seconds, the
  context widens one step as it does without AI. In "Practice with this PDF", making questions with AI asks
  Claude to write questions (with answers, explanations and quoted sources) from the pages you chose; the
  passage each question quotes is checked against those pages, and the questions are kept in the app's
  question bank on the iPad.
- **Who handles a request, and why:** requests are used only to choose which context range "Widen context"
  shows and to write questions from the text of the pages you choose. Each request passes through three
  parties in turn:
  1. **Our relay server**, a small program we run on Cloudflare Workers (Cloudflare, Inc., United States;
     privacy contact dpo@cloudflare.com). It holds the API key so the app carries none. It checks only the
     request's path, the fixed app value (below), that it asks for an allowed Claude model, its output length
     limit and its size, and passes the text and instruction on unchanged. Our relay program does not store or
     log the text, the answer or the app details. Your IP address is used only briefly by Cloudflare's rate-limiting
     feature to count requests per minute, and we do not store or log it.
  2. **BizRouter**, an LLM API gateway in the Republic of Korea run by AI3 Inc. (주식회사 AI3, Yeongdong-daero 85-gil 34,
     Gangnam-gu, Seoul; privacy contact privacy@ai3.kr). Its gateway and records are in Seoul (AWS).
  3. **The service that runs Claude** (Anthropic, PBC's models). BizRouter sends the request either through
     **Anthropic, PBC**'s Claude API (United States; privacy contact privacy@anthropic.com) or through **Amazon
     Bedrock** of **Amazon Web Services, Inc.** (AWS, United States).

  We request only Anthropic's Claude models.
- **Sent when you tap "Widen context" with AI Assist on:** the text of the candidate ranges the app cut from
  that card's page, from a few lines up to the whole text of the page, all in one request, so every request
  includes the whole text of that page (the answer and its other appearances masked); the masked answer's
  characters; and a fixed instruction. Each request also carries the app identifier (bundle ID), the app
  version and the iPadOS version (the package's User-Agent, with its own and the Swift version) and a fixed
  value built into the app that is the same for every install, so it identifies the app, not you or your iPad.
  As with any internet connection, the request comes from your IP address. Our relay server receives the IP
  address, the User-Agent and the fixed value and passes none of them on; BizRouter and the service that runs
  Claude (Anthropic or AWS) receive the text, the instruction and the model settings.
- **Sent when you make questions with AI:** for each request, the text of the pages you chose (each line's
  text, its page number and position on the page, and a number for whether it carries a mask, highlight,
  handwriting or another mark), the text of notes and text boxes on those pages (including notes another app
  left in the PDF), the question text of up to 12 questions already made in the same run (so they are not
  repeated), the question type,
  count and target score, and a fixed instruction. Masked answers are **not** hidden here. Regions and terms
  you exclude are left out. Before anything is sent, the app shows the pages and text it will send and asks
  you to confirm. Each request carries the same app details, fixed app value and IP address as above.
- **Not sent:** page images, handwriting, the text the app reads from handwriting on the iPad, material or
  file names, account details (the app has no accounts), and any device identifier or access token. If handwriting is already part of a PDF's text,
  as in PDFs exported from other note apps, that text is sent with the rest of the page's text. "Widen
  context" sends only that card's page; making questions sends only the pages you chose.
- **Transfer abroad:** text is sent over encrypted connections (HTTPS) each time. Our relay server runs in the
  Cloudflare data center that receives the request, which may be outside the Republic of Korea. BizRouter
  handles it in Seoul and sends the text and instruction to Claude through Anthropic's API or Amazon Bedrock (AWS);
  either may process them in the United States or other countries, and processing only inside the Republic of
  Korea is not guaranteed.
- **Consent:** the first time you turn the switch on, the app shows on one screen who handles the requests
  (our relay server, BizRouter, and Anthropic's API or Amazon Bedrock) and why, what is sent and what is not, the
  transfer abroad and what BizRouter and Anthropic keep (in bold), a caution, how to
  decline or turn it off, and the privacy policy. "Agree and Turn On" works only after you confirm "I am 14 or
  older"; Cancel leaves it off. Nothing is sent before you agree. The app
  keeps the version of the screen you agreed to: when the screen changes in substance, the switch shows off,
  nothing is sent, and turning it on asks again. The same agreement covers "Widen context" and making questions; making questions
  also asks each time before it sends. Settings → AI Assist → "Review What Is Sent" shows the same
  screen again at any time.
- **Declining:** if you do not agree, or turn it off, everything else works as before: "Widen context"
  widens one step at a time without AI, and questions can be made without AI with local generation. Turning
  it off stops sending from the next request.
- **Check before sending:** "Widen context" masks only the answer; making questions masks nothing. The app
  filters nothing else. Turn AI Assist off for material that contains other people's names or contact
  details, identifiable patient information or resident registration numbers.
- **Children:** AI Assist is for users 14 or older; the consent screen asks you to confirm this.
- **Daily limit:** up to 50 "Widen context" requests per device per day; past that, "Widen context" works
  without AI. Making questions is counted separately: up to 12 requests per device per day (one request
  writes up to 5 questions); past that, the rest waits for the next day. Both are counted on the iPad. The
  BizRouter key our relay server uses also has a daily limit on the total cost of all AI requests; once it is
  reached, the app works without AI as described under "Declining".
- **What our relay server keeps:** nothing. Our relay program passes each request and answer through and does
  not store or log them, your IP address or the app details. The IP address is used only to count requests per
  minute (see above).
- **What BizRouter keeps:** we have turned off BizRouter's "audit log" storage. BizRouter states that with it
  off it does not store request or response text, and that it keeps billing records (such as time, model, token
  counts, charge and result) as the basis for billing, for a period it does not state, and records of how a
  request was handled, such as retries and fallbacks, for 90 days. Its terms also allow temporary logs for fixing
  errors for up to 30 days, and retention required by law
  ([data policy](https://bizrouter.ai/docs/data-policy), [terms](https://bizrouter.ai/terms),
  [privacy policy](https://bizrouter.ai/privacy)). BizRouter states that it does not turn on training or
  data-sharing options when it calls a provider's API.
- **What Anthropic keeps (when BizRouter uses Anthropic's API):** Anthropic states that it deletes API inputs
  and outputs within 30 days by default. A service with longer retention, a separate agreement, usage-policy enforcement or legal
  requirements can change that period. For requests flagged by its automated safety systems, it may keep
  inputs and outputs for up to two years and classification scores for up to seven years. Anthropic states
  that data it retains is never used for model training without express permission
  ([retention](https://privacy.claude.com/en/articles/7996866-how-long-do-you-store-my-organization-s-data),
  [API data retention](https://platform.claude.com/docs/en/manage-claude/api-and-data-retention)).
  BizRouter's data policy gives the same 30 days from receipt or generation (up to two years when flagged for a
  policy violation). Our relay passes each request through and keeps no copy.
- **When BizRouter uses Amazon Bedrock:** the request is handled by AWS under its policies for Amazon Bedrock
  rather than under Anthropic's retention above.
- **Case records (optional, off by default):** Settings → AI Assist → "Keep case records" keeps, for each "Widen
  context" AI request (not for making questions), the text that was sent, the masked answer, the range the app chose, the range Claude chose, the
  model settings and the timing, in one file on the iPad (the newest 1,000). The file holds no material
  name, page number, identifier or time. The app never sends it anywhere; it leaves the iPad only when you
  export it through the share sheet, or when iPadOS includes it in your own iCloud or computer backup (it is
  not in the app's backup zip). You can delete it in Settings, and "Delete all data" deletes it.
- **Protection by third parties:** every third party that handles AI Assist requests (Cloudflare, Inc., AI3 Inc. as
  operator of BizRouter, Anthropic, PBC, and Amazon Web Services, Inc. when Amazon Bedrock is used) provides the same or equal protection of user data as stated in this
  policy. Each handles the data only for the purposes above and keeps it only as described above.

## Your controls

- **Back up:** “Export backup” in Settings & Backup makes a ZIP of your materials, handwriting, cards,
  questions and review history. The ZIP has no password and contains the files as stored on the iPad, including the unlocked copy of any
  password-protected PDF you imported. Choose a private destination. Restoring the iPad from an iCloud or computer backup also brings the app’s data back.
- **Restore:** In Settings & Backup, select an app backup ZIP with “Restore from Backup” and confirm
  “Schedule Restore”. The app replaces its study data on the iPad after you quit and reopen it. App settings
  stay as they were. Pendeck keeps the previous data on this iPad outside the device backup. “Go Back to
  Previous Data” swaps the two sets of data when you quit and reopen. “Delete Previous Data” and “Delete all
  data” remove the kept copy. Restoring another ZIP replaces the kept copy with the data it just replaced.
- **Export:** "Export data (JSON)" writes an open format other tools can read; cards export to CSV;
  documents export as PDFs with your handwriting, text boxes and images (all pages, this page only or a page
  range), or as the original PDF without your handwriting.
- **AI Assist:** turn off the switch in Settings → AI Assist; nothing is sent from the next request. "Delete all data"
  also forgets that you agreed, so the app asks again the next time you turn it on.
- **Requests already sent:** requests carry no identifier of you or your device, so neither we nor BizRouter,
  Anthropic or AWS can find and delete a particular user's requests. The text sent is deleted after the periods in
  "What BizRouter keeps" and "What Anthropic keeps" (or under AWS's Amazon Bedrock policies). For questions about deletion or withdrawing consent, write to
  pendeck.support@gmail.com.
- **Reminders:** Settings → Review schedule → "Review reminders" turns them off and removes the scheduled
  ones; iOS Settings → Notifications can also turn off the app's notifications.
- **Delete a material:** it moves to Recently Deleted in the sidebar. "Delete Permanently" or "Empty Recently
  Deleted" there removes it from the iPad at once; otherwise it is removed after 30 days (see above).
- **Delete:** Settings → Erase data → "Delete all data" irreversibly removes everything the app
  stored on this iPad, including scheduled review reminders, a backup being restored and the data kept from
  before a restore. Deleting the app also removes all of it from this iPad. Files you exported, device backups and
  requests already sent with AI Assist are not affected. On an iPad that has used iCloud Sync, the button is "Erase
  Only This Device": it erases this iPad's data the next time you open the app and leaves the copy in iCloud (see
  "iCloud Sync").

## Not a medical device

This app is a **learning aid**, not a tool for diagnosis, treatment or prescribing. Do not rely on
its content for patient care.

## Contact

E-mail: pendeck.support@gmail.com · Support page: https://changyoungduo.github.io/pendeck-support/ — questions
and problem reports go to that address (GitHub issues, listed on the support page, also work).

## Changes to this policy

If this policy changes, we post the new version and its effective date on this page.
