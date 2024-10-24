### README.md - 소방청 구조 활동 현황 분석 프로젝트

# 소방청 구조 활동 현황 분석

이 프로젝트는 **소방청 구조 활동 현황** 데이터를 분석하여, 사건 발생 시점과 장소, 사고 원인 및 사고 종류와 같은 다양한 요소를 시각화하고 통계적으로 분석하는 것을 목표로 합니다. 이를 통해 구조 활동 패턴과 사고 발생 경향을 파악하고, 더 나은 정책 제안 및 대응 전략 수립에 기여할 수 있는 인사이트를 도출합니다.

데이터는 [공공데이터 포털](https://www.data.go.kr/data/15062386/fileData.do)에서 제공됩니다.

추가데이터 : https://www.data.go.kr/data/15072140/fileData.do

## 주요 분석 항목
- **신고년월일**: 신고 접수 날짜
- **신고시각**: 신고 접수 시각
- **출동년월일**: 구조대 출동 날짜
- **출동시각**: 구조대 출동 시각
- **발생장소_시/구/동**: 사고 발생 위치(시, 구, 동)
- **사고원인**: 사고의 주요 원인
- **사고원인코드명_사고종별**: 사고 분류 코드와 구체적인 사고 종류

## 프로젝트 목적
1. **데이터 분석 및 시각화**: 구조 활동 데이터를 분석하여 시간대, 지역별 사고 발생 패턴을 시각적으로 표현하고, 이를 통해 인사이트를 도출합니다.
2. **정책 제안 및 대응 전략 수립**: 사고 원인 및 발생 위치에 대한 분석을 통해 구조 활동을 최적화하고 예방책 마련에 기여할 수 있는 전략을 제시합니다.
3. **사고 예방 및 대응 강화**: 데이터 분석을 통해 사고 발생 위험 지역 및 시간대를 파악하여 소방청의 예방 활동을 강화하고 대응 체계를 개선합니다.

## 사용된 주요 라이브러리
- **pandas**: 데이터 전처리 및 분석
- **Seaborn**: 사고 발생 패턴 및 원인에 대한 시각화
- **matplotlib**: 데이터 시각화 및 추가적인 세부 그래프 생성

## 분석 과정
1. **데이터 전처리**:
   - 결측값 처리 및 중복 데이터 제거
   - 날짜 및 시각 형식 변환
   - 필요한 정보에 따라 데이터 필터링 및 가공
   
2. **데이터 분석**:
   - 시간대별 신고 및 출동 현황 분석
   - 지역별 사고 발생 빈도 분석
   - 사고 원인 및 종류에 따른 구조 활동 분석

3. **데이터 시각화**:
   - 사고 발생 시간대, 지역별 사고 빈도 그래프 생성
   - 사고 원인 및 종류에 따른 구조 활동 패턴 시각화

## 실행 방법
1. Python 3.8 이상의 환경에서 프로젝트를 클론합니다:

   ```bash
   git clone https://github.com/yourusername/FireRescueAnalysis.git
   cd FireRescueAnalysis
   ```

2. 필요한 라이브러리를 설치합니다:

   ```bash
   pip install -r requirements.txt
   ```

3. Jupyter Notebook을 실행하거나 Python 스크립트를 실행하여 분석을 시작합니다:

   ```bash
   jupyter notebook
   ```

## 프로젝트 결과
- 시간대 및 지역별 사고 발생 패턴에 대한 분석을 통해 주요 사고 발생 시간과 장소를 파악했습니다.
- 사고 원인 및 종류에 따른 구조 활동의 빈도 분석을 통해 사고 유형별로 차별화된 대응 방안을 도출할 수 있었습니다.
- 분석 결과를 바탕으로 소방청의 예방 및 대응 활동을 강화할 수 있는 전략을 제안합니다.

## 데이터 출처
이 프로젝트에서 사용된 데이터는 **대한민국 공공데이터 포털**에서 제공된 소방청 구조 활동 데이터를 기반으로 합니다.

## 기여 방법
이 프로젝트에 기여하고 싶다면 포크를 한 후 Pull Request를 제출해 주세요. 버그 리포트나 새로운 기능 제안은 이슈 트래커를 통해 가능합니다.
