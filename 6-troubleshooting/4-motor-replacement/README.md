# 6.4. 모터 및 감속기 교환


<table>
<thead>
  <tr>
    <td>
    <div align="center">
      <img src="../../_assets/주의표시.png" width = 80 height = 80>
    </div>
    </td>
    <td colspan="4">본 로봇은 암의 자세 유지용 브레이크가 모터에 내장되어 있으므로 모터를 분리하면 암이 낙하합니다. 이런 낙하를 방지하기 위해 크레인 등으로 암을 매달거나, 고정용 Pin을 삽입하여 제 1암과 제2암을 고정시키는 등의 안전대책을 필히 행해주십시오.<p>

  로봇 정지 직후 모터에 접촉하는 경우에는, 모터 온도를 확인하십시오. 모터와 감속기의 무게는 다음과 같습니다. 모터 운반 시 유의하십시오.<p>

  감속기를 교환하는 경우에는, 감속기의 먼지 유입 방지와 감속기 체결 볼트를 규정된 토크로 체결해야 함을 유의하십시오. 또한, 유출된 그리스만큼 신규로 보충해주십시오.
</td>
  </tr>
</thead>
</table>  

<br></br>
표 6-2 무게(모터)
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-jafi{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-jafi">축</th>
    <th class="tg-jafi">S</th>
    <th class="tg-jafi">H</th>
    <th class="tg-jafi">V</th>
    <th class="tg-jafi">R2</th>
    <th class="tg-jafi">B</th>
    <th class="tg-jafi">R1</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix">HA006B</td>
    <td class="tg-nrix">5.3Kg</td>
    <td class="tg-nrix">7.2kg</td>
    <td class="tg-nrix">3.1kg</td>
    <td class="tg-nrix">0.9Kg</td>
    <td class="tg-nrix">0.9kg</td>
    <td class="tg-nrix">0.9kg</td>
  </tr>
  <tr>
    <td class="tg-nrix">HA006L</td>
    <td class="tg-nrix">9.5kg</td>
    <td class="tg-nrix">9.5kg</td>
    <td class="tg-nrix">6.7kg</td>
    <td class="tg-nrix">1.3kg</td>
    <td class="tg-nrix">0.9kg</td>
    <td class="tg-nrix">0.9kg</td>
  </tr>
</tbody>
</table>

<br>
표 6-3 무게(감속기)
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-jafi{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-jafi">축</th>
    <th class="tg-jafi">S</th>
    <th class="tg-jafi">H</th>
    <th class="tg-jafi">V</th>
    <th class="tg-jafi">R2</th>
    <th class="tg-jafi">B</th>
    <th class="tg-jafi">R1</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix">HA006B</td>
    <td class="tg-nrix">5.9Kg</td>
    <td class="tg-nrix">5.9kg</td>
    <td class="tg-nrix">3.8kg</td>
    <td class="tg-nrix">0.9Kg</td>
    <td class="tg-nrix">0.12kg</td>
    <td class="tg-nrix">0.12kg</td>
  </tr>
  <tr>
    <td class="tg-nrix">HA006L</td>
    <td class="tg-nrix">19.5kg</td>
    <td class="tg-nrix">13.5kg</td>
    <td class="tg-nrix">5.9kg</td>
    <td class="tg-nrix">2.1kg</td>
    <td class="tg-nrix">0.15kg</td>
    <td class="tg-nrix">0.15kg</td>
  </tr>
</tbody>
</table>


<blockquote>
<table border="0">
<thead>
  <tr>
    <td>
    <div align="center">
      <img src="../../_assets/주의표시.png" width = 80 height = 80>
    </div>
    </td>
    <td colspan="4">이 작업은 운전 준비 [ON] 상태에서 시행할 부분이 있습니다. 그러므로 2인 1조로 작업을 실시하며 한 사람은 언제라도 비상정지 버턴을 누를 자세를 취하고, 다른 한 사람은 로봇의 동작에 특히 주의하면서 신속하게 작업을 하십시오. 또한, 작업 전에는 미리 위험을 벗어날 장소를 확인하여 주십시오.
</td>
  </tr>
</thead>
</table>
</blockquote>
