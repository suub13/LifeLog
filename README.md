
<html>
<head>
<meta charset="utf-8">
<title>2Lifelog Dropdown Test</title>
<style type="text/css"></style>
<style>
  select{
    width: 200px;
    margin:6px;
    text-align-last: center
  }
  option:first-child{
    display:none
  }

</style>
</head>

<body>
  <br><br>
  <h1 style="text-align:center">라이프로그 데이터</h1>
<!--  <h2 style="text-align:center;color:grey">원하는 정보를 아래에서 찾아보세요.</h2>
  <p style="text-align:center">데이터 버튼을 클릭하면 원하는 정보를 선택할 수 있습니다. </p>-->
<br>
<form action="">
  <table align="center">
    <thead>
      <tr>
        <th colspan="4" style="font-size: 12px;color:olive">데이터 버튼을 클릭하면 분석을 위한 항목들을 선택할 수 있습니다.</th>
      </tr>
    </thead>
    <tbody>
<tr>
  <td>&nbsp;</td>
</tr>
      <tr>
      <td>
        <button style="width:140px"><label for="health medical examination data" >건강검진 데이터</label></button>
      </td>
          <!-- <button onclick="myFunction()"&nbsp; &nbsp; 건강검진 데이터 &nbsp;></button> -->
      <td>
        <select name="건강검진 데이터" id="health medical examination data" value="choose your option">
          <option value="option">Please Select</option>
          <option value="회사명">회사명</option>
          <option value="신장">신장</option
          <option value="체중 ">체중 </option>
          <option value="허리둘레">허리둘레</option>
          <option value="체질량지수">체질량지수</option>
          <option value="시력(좌) ">시력(좌) </option>
          <option value="시력(우) ">시력(우) </option>
          <option value="청력(좌) ">청력(좌) </option>
          <option value="청력(우) ">청력(우) </option>
          <option value="혈압(최고)">혈압(최고)</option>
          <option value="혈압(최저)">혈압(최저)</option>
          <option value="혈색소량">혈색소량</option>
          <option value="혈당 ">혈당 </option>
          <option value="혈청지오티 ">혈청지오티 </option>
          <option value="혈청지피티 ">혈청지피티 </option>
          <option value="감마지티피">감마지티피</option>
          <option value="총콜레스테롤 ">총콜레스테롤 </option>
          <option value="중성지방">중성지방</option>
          <option value="HDL콜레스테롤">HDL콜레스테롤</option>
          <option value="LDL-콜레스테롤">LDL-콜레스테롤</option>
          <option value="크레아티닌">크레아티닌</option>
          <option value="요단백 ">요단백 </option>
          <option value="신사구체여과율">신사구체여과율</option>
          <option value="흉부방사선(P-A)">흉부방사선(P-A)</option>
        </select>
      </td>
      <td>&nbsp;</td>
      </tr>
      <tr>
        <td>
          <button style="width:140px"><label for="genomic data">유전자 데이터</label></button>
        </td>
        <td><select name="유전자 데이터" id="genomic data">
          <option value="option">Please Select</option>
          <optgroup label="건강관리">
          <option value="비만">비만</option>
          <option value="체지방율">체지방율</option>
          <option value="체질량지수">체질량지수</option>
          <option value="혈당 ">혈당 </option>
          <option value="혈압">혈압</option>
          <option value="중성지방농도">중성지방농도</option>
          <option value="콜레스테롤">콜레스테롤</option>
          <option value="요산치">요산치</option>
          <option value="퇴행성 관절염증 감수성">퇴행성 관절염증 감수성</option>
          <option value="멀미">멀미</option>
          <optgroup label="식습관">
          <option value="식욕">식욕</option>
          <option value="포만감">포만감</option>
          <option value="단맛 민감도">단맛 민감도</option>
          <option value="쓴맛 민감도">쓴맛 민감도</option>
          <option value="짠맛 민감도">짠맛 민감도</option>
          <optgroup label="영양소">
          <option value="비타민C 농도">비타민C 농도</option>
          <option value="비타민D 농도">비타민D 농도</option>
          <option value="마그네슘 농도">마그네슘 농도</option>
          <option value="아연 농도">아연 농도</option>
          <option value="철 저장 및 농도">철 저장 및 농도</option>
          <option value="칼륨 농도">칼륨 농도</option>
          <option value="칼슘 농도">칼슘 농도</option>
          <option value="아르기닌 농도">아르기닌 농도</option>
          <option value="지방산 농도">지방산 농도</option>
          <optgroup label="운동">
          <option value="근력 운동 적합성">근력 운동 적합성</option>
          <option value="유산소 운동 적합성">유산소 운동 적합성</option>
          <option value="지구력운동 적합성">지구력운동 적합성</option>
          <option value="근육발달능력">근육발달능력</option>
          <option value="단거리 질주 능력">단거리 질주 능력</option>
          <option value="악력">악력</option>
          <option value="운동후 회복능력">운동후 회복능력</option>
          <optgroup label="개인 특성">
          <option value="알코올 대사">알코올 대사</option>
          <option value="알코올 의존성">알코올 의존성</option>
          <option value="알코올 홍조">알코올 홍조</option>
          <option value="와인선호도">와인선호도</option>
          <option value="니코틴 대사">니코틴 대사</option>
          <option value="니코틴 의존성">니코틴 의존성</option>
          <option value="카페인 대사">카페인 대사</option>
          <option value="카페인 의존성">카페인 의존성</option>
          <option value="불면증">불면증</option>
          <option value="수면습관/시간">수면습관/시간</option>
          <option value="아침형, 저녁형 인간">아침형, 저녁형 인간</option>
          <option value="통증 민감성">통증 민감성</option>
          <optgroup label="피부/모발">
          <option value="기미/주근깨">기미/주근깨</option>
          <option value="색소침착">색소침착</option>
          <option value="여드름 발생">여드름 발생</option>
          <option value="피부염증">피부염증</option>
          <option value="피부노화">피부노화</option>
          <option value="태양 노출 후 태닝 반응">태양 노출 후 태닝 반응</option>
          <option value="튼살/각질">튼살/각질</option>
          <option value="남성형 탈모">남성형 탈모</option>
          <option value="모발 굵기">모발 굵기</option>
          <option value="원형 탈모">원형 탈모</option>
          <optgroup label="유전자 혈통분석">
          <option value="조상찾기">조상찾기</option>
        </td>
        <td>&nbsp;</td>
      </tr>
      <tr>
        <td><button style="width:140px"><label for="survey data">설문지 데이터</label></button></td>
        <td><select name="설문지 데이터" id="survey data">
          <option value="option">Please Select</option>
          <optgroup label="인적사항">
          <option value="성별">성별</option>
          <option value="연령(만)">연령(만)</option>
          <optgroup label="거주특성">
          <option value="거주 특성">거주 특성</option>
          <optgroup label="실내환경">
          <option value="건물형태">건물형태</option>
          <option value="건축년도">건축년도</option>
          <option value="입주년도">입주년도</option>
          <option value="가족수">가족수</option>
          <option value="방개수">방 개수</option>
          <option value="난방/ 취사연로">난방/ 취사연로</option>
          <option value="환기">환기</option>
          <option value="가전제품 사용">가전제품 사용</option>
          <option value="부엌 구분">부엌 구분</option>
          <option value="배기팬">배기팬</option>
          <option value="벽 얼룩,곰팡이">벽 얼룩,곰팡이</option>
          <option value="소파">소파</option>
          <option value="바닥재">바닥재</option>
          <option value="바닥깔개">바닥깔개</option>
          <option value="침대">침대</option>
          <option value="커튼">커튼</option>
          <option value="리모델링">리모델링</option>
          <option value="애완동물">애완동물</option>
          <option value="실내실물">실내실물</option>
          <optgroup label="생활습관">
          <option value="흡연여부">흡연여부</option>
          <option value="타인실내흡연여부">타인실내흡연여부</option>
          <option value="직상실내흡연여부">직상실내흡연여부</option>
          <option value="음주빈도">음주빈도</option>
          <option value="운동여부">운동여부</option>
          <option value="격렬한활동여부">격렬한활동여부</option>
          <option value="중간활동여부">중간활동여부</option>
          <option value="걷기여부">걷기여부</option>
          <optgroup label="질병 및 약물 복용력">
          <option value="건강상태">건강상태</option>
          <option value="질병여부">질병여부</option>
          <optgroup label="식이습관">
          <option value="채소류">채소류</option>
          <option value="과일류">과일류</option>
          <option value="해조류">해조류</option>
          <optgroup label="사회, 경제, 인구학적 특징">
          <option value="학력">학력</option>
          <option value="결혼상태">결혼상태</option>
          <option value="가구수입">가구수입</option>
          <option value="경제적수준">경제적수준</option>
          <option value="직업경험여부">직업경험여부</option>
          <optgroup label="우을증상">
          <option value="우울증상">우울증상</option>
          <optgroup label="숙면">
          <option value="주중 숙면 시간">주중 숙면 시간</option>
          <option value="주말 숙면 시간">주말 숙면 시간</option>
        </select></td>
        <td>&nbsp;</td>
      
      <tr>
        <td><button style="width:140px"><label for="smartband data">스마트밴드 데이터</label></button></td>
        <td><select name="스마트밴드 데이터" id="smartband data">
          <option vakye="option">Please Select</option>
          <option value="health.caffeine_intake">health.caffeine_intake</option>
          <option value="health.food_info">health.food_info</option>
          <option value="health.food_intake">health.food_intake</option>
          <option value="health.nutrition">health.nutrition</option>
          <option value="health.water_intake">health.water_intake</option>
          <option value="shealth.calories_burned.details">shealth.calories_burned.details</option>
          <option value="shealth.exercise">shealth.exercise</option>
          <option value="shealth.food_frequent">shealth.food_frequent</option>
          <option value="health.sleep_stage">health.sleep_stage</option>
          <option value="shealth.insight.hourly_accumulated_active_time">shealth.insight.hourly_accumulated_active_time</option>
          <option value="shealth.sleep">shealth.sleep</option>
          <option value="shealth.stress">shealth.stress</option>
          <option value="shealth.tracker.heart_rate">shealth.tracker.heart_rate</option>
          <option value="shealth.tracker.oxygen_saturation">shealth.tracker.oxygen_saturation</option>
          <option value="shealth.tracker.pedometer_day_summary">shealth.tracker.pedometer_day_summary</option>
        </select></td>
        <td><div style="text-align:center">
        <input type="submit" value="확인" style="width:90px">
        </div></td>
      </tr>
    </tbody>
  </table>
  <br>


  <h2 style="text-align:center">데이터 구성</h2>
<table align="center" border="2"  style="text-align:center; margin:0px auto;">
  <tbody>
    <tr>
      <td >&nbsp;</td>
      <td width="125">건강검진 데이터</td>
      <td width="110">유전자 데이터</td>
      <td width="110">설문지 데이터</td>
      <td width="140">스마트밴드 데이터</td>
    </tr>
    <tr>
      <td width="80">항목 개수</td>
      <td>24</td>
      <td>15</td>
      <td>43</td>
      <td>54</td>
    </tr>
  </tbody>
</table>
<br>
<p style="text-align:center">
<img align="center" src="성별데이터 예시.png" width="330" alt="성별 데이터">
<img align="center" src="나이데이터 예시.png" width="330" alt="나이별 데이터">
</p>
<br>
</body>
</html>
