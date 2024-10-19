### README.md - 소방청 구조 활동 현황 분석 프로젝트

# 소방청 구조 활동 현황 분석

이 프로젝트는 소방청 구조 활동 현황 데이터를 분석하여, 사건이 발생한 날짜와 시간, 위치, 사고 원인 및 사고 종류와 같은 정보를 시각화하고 분석하는 것을 목표로 합니다. 이를 통해 구조 활동의 패턴과 사고 발생 동향을 파악하고, 향후 개선 방향을 모색하는 데 도움이 되는 인사이트를 도출합니다.

https://www.data.go.kr/data/15062386/fileData.do

## 주요 컬럼
- **신고년월일**: 신고가 접수된 날짜
- **신고시각**: 신고가 접수된 시각
- **출동년월일**: 구조대가 출동한 날짜
- **출동시각**: 구조대가 출동한 시각
- **발생장소_시/구/동**: 사고가 발생한 장소의 시, 구, 동 정보
- **사고원인**: 사고가 발생한 주요 원인
- **사고원인코드명_사고종별**: 사고의 구체적인 분류

## 프로젝트 목적
1. **데이터 분석 및 시각화**: 구조 활동 데이터의 주요 패턴을 시각적으로 표현하고 분석하여, 지역별 사고 발생 건수, 시간대별 출동 건수 등을 파악.
2. **인사이트 도출**: 소방 구조 활동의 주요 패턴을 통해 사고의 원인과 발생 장소를 분석하고, 예방책이나 대응 방안을 제시.
3. **활용 가능성**: 해당 분석 결과는 소방청의 정책 결정, 예방 활동 강화, 지역별 대응 전략 수립에 활용 가능.

## 사용한 라이브러리
- **pandas**: 데이터 전처리 및 분석에 사용.
- **Seaborn**: 데이터 시각화에 사용. 특히 지역별, 시간대별 사고 발생 패턴을 시각적으로 표현.
- **matplotlib**: Seaborn과 함께 데이터를 더욱 세밀하게 시각화할 때 사용.

## 분석 과정
1. **데이터 전처리**:
   - 결측치 처리, 중복 데이터 제거.
   - 날짜 및 시각 데이터의 형식 변환.
   
2. **데이터 분석**:
   - 신고 시간 및 출동 시간에 따른 구조 활동 패턴 분석.
   - 지역별 사고 발생 빈도 분석.
   - 사고 원인 및 사고 종류에 따른 구조 활동 현황 분석.

3. **데이터 시각화**:
   - 시간대별, 지역별 사고 발생 건수 시각화.
   - 사고 원인 및 사고 종류에 따른 시각적 분포 분석.

## 실행 방법
1. Python 3.8 이상이 설치된 환경에서 프로젝트를 클론합니다.

   ```bash
   git clone https://github.com/yourusername/FireRescueAnalysis.git
   cd FireRescueAnalysis
   ```

2. 필요한 라이브러리를 설치합니다.

   ```bash
   pip install -r requirements.txt
   ```

3. Jupyter Notebook 또는 Python 스크립트를 실행하여 분석을 시작합니다.

   ```bash
   jupyter notebook
   ```

## 데이터 출처
소방청 구조 활동 데이터는 대한민국 정부의 **공공데이터 포털**에서 제공된 데이터를 기반으로 분석하였습니다.

## 기여 방법
이 프로젝트에 기여하고 싶다면, 포크를 하고 Pull Request를 보내주세요. 또는 이슈 트래커를 통해 버그를 보고하거나 새로운 기능을 제안할 수 있습니다.

