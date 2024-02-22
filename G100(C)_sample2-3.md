![](G100(C)_sample2_a1.001.png)

**응용 기능 사용하기![](G100(C)_sample2_a1.002.png)**

**5.1  보조 주파수 운전** 

주속 주파수와 보조속 주파수를 동시에 사용하여 다양한 연산 조건을 가지는 운전 주파수를 사용할 수 있습니다. 이 때, 주속은 주 운전 주파수 설정에 이용하고 보조속은 주속 운전 상태에서의 미세 속도 조정 등에 이용합니다. 



<table><tr><th colspan="1"><b>그룹</b> </th><th colspan="1"><b>코드</b> </th><th colspan="1"><b>명칭</b> </th><th colspan="2"><b>설정 값</b> </th><th colspan="1"><b>설정 범위</b> </th><th colspan="1"><b>단위</b> </th></tr>
<tr><td colspan="1">운전 </td><td colspan="1">Frq </td><td colspan="1">주파수 설정 방법 </td><td colspan="1">0 </td><td colspan="1">Keypad-1 </td><td colspan="1">0~8 </td><td colspan="1">- </td></tr>
<tr><td colspan="1" rowspan="3">bA </td><td colspan="1">01 </td><td colspan="1">보조속 지령 설정 방법 </td><td colspan="1">1 </td><td colspan="1">V1 </td><td colspan="1">0~4 </td><td colspan="1">- </td></tr>
<tr><td colspan="1">02 </td><td colspan="1">보조속 지령 작동 선택 </td><td colspan="1">0 </td><td colspan="1">M+(G*A) </td><td colspan="1">0~7 </td><td colspan="1">- </td></tr>
<tr><td colspan="1">03 </td><td colspan="1">보조속 지령 게인 </td><td colspan="1">0\.0 </td><td colspan="1"></td><td colspan="1">-200.0~200.0 </td><td colspan="1">% </td></tr>
<tr><td colspan="1">In </td><td colspan="1">65~ 71 </td><td colspan="1">Px 단자 기능 설정 </td><td colspan="1">40 </td><td colspan="1">dis Aux Ref </td><td colspan="1">0~52 </td><td colspan="1">- </td></tr>
</table>

예를 들어, 위의 표와 같이 주속과 보조속을 설정한 경우, 운전 그룹 Frq 코드를  ![](G100(C)_sample2_a1.003.png)0(Keypad-1)으로 설정하여 주속 30.00Hz로 운전 중, V1 단자에 -10~+10V 전압을  공급하고 이에 대한 게인을 5%로 설정하면 27.00~33.00Hz까지 미세 조정이  

가능합니다[In.01~16까지의 변수가 초기 값이고, In.06 V1 Polarity를 1(Bipolar)로 설정].  

**보조 주파수 운전 설정 상세** 

**코드 및 기능  설명 ![](G100(C)_sample2_a1.004.png)**

보조속 지령으로 사용할 입력 종류를 선택합니다. 



|설정 |기능 ||
| - | - | :- |
|0 |None |보조속 작동을 하지 않습니다. |
|1 |V1 |제어 단자대의 전압 입력 단자를 보조속 지령으로 선택합니다. |
|3 |V0 |키패드의 볼륨 다이얼을 보조속 지령으로 선택합니다. |
|4 |I2 |I2 단자의 전류 입력을 보조속 지령으로 선택합니다. |

bA.01 Aux Ref Src 

115 ![](G100(C)_sample2_a1.005.png)

**기술 사양 ![](G100(C)_sample2_a1.006.png)**

**11.4 주변 기기** 

**G100 배선용 차단기/누전 차단기/전자 접촉기 모델명(LS ELECTRIC)** 



<table><tr><th colspan="2" rowspan="2"><b>제품(kW)</b> </th><th colspan="3"><b>배선용 차단기</b> </th><th colspan="4"><b>누전 차단기</b> </th><th colspan="3"><b>전자 접촉기</b> </th></tr>
<tr><td colspan="1"><b>모델명</b> </td><td colspan="1"><b>정격(A)</b> </td><td colspan="1"><b>상세모델명</b> </td><td colspan="2"><b>모델명</b> </td><td colspan="2"><b>정격(A)</b> </td><td colspan="2"><b>모델명</b> </td><td colspan="1"><b>정격(A)</b> </td></tr>
<tr><td colspan="1" rowspan="11">3상 200V 급 </td><td colspan="1">0\.4 </td><td colspan="1" rowspan="5">UTE100H</td><td colspan="1" rowspan="3">15 </td><td colspan="1" rowspan="3">UTE100·H·FTU·15·3P·UL </td><td colspan="1">5 </td><td colspan="2" valign="bottom">MC-6a </td><td colspan="2">9 </td></tr>
<tr><td colspan="1">0\.75 </td><td colspan="2" rowspan="4" valign="top">EBS33c </td><td colspan="2">10 </td><td colspan="2">MC-9a, MC-9b </td><td colspan="1">11 </td></tr>
<tr><td colspan="1">1\.5 </td><td colspan="2">15 </td><td colspan="2">MC-18a, MC-18b </td><td colspan="1">18 </td></tr>
<tr><td colspan="1">2\.2 </td><td colspan="1">20 </td><td colspan="1">UTE100·H·FTU·20·3P·UL </td><td colspan="2">20 </td><td colspan="2">MC-22b </td><td colspan="1">22 </td></tr>
<tr><td colspan="1">4\.0 </td><td colspan="1">30 </td><td colspan="1">UTE100·H·FTU·30·3P·UL </td><td colspan="2">30 </td><td colspan="2">MC-32a </td><td colspan="1">32 </td></tr>
<tr><td colspan="1">5\.5 </td><td colspan="1" rowspan="6">UTS150H</td><td colspan="1">50 </td><td colspan="1">UTS150·H·FTU·50·3P·UL </td><td colspan="2">EBS53c </td><td colspan="2">50 </td><td colspan="2">MC-50a </td><td colspan="1">55 </td></tr>
<tr><td colspan="1">7\.5 </td><td colspan="1">60 </td><td colspan="1">UTS150·H·FTU·60·3P·UL </td><td colspan="2">EBS63c </td><td colspan="2">60 </td><td colspan="2" valign="bottom">MC-65a </td><td colspan="1">65 </td></tr>
<tr><td colspan="1">11 </td><td colspan="1">80 </td><td colspan="1">UTS150·H·FTU·80·3P·UL </td><td colspan="2" rowspan="2">EBS103c </td><td colspan="2">100 </td><td colspan="2">MC-85a </td><td colspan="1">85 </td></tr>
<tr><td colspan="1">15 </td><td colspan="1">100 </td><td colspan="1">UTS150·H·FTU·100·3P·UL </td><td colspan="2">125 </td><td colspan="2">MC- 130a </td><td colspan="1">130 </td></tr>
<tr><td colspan="1">18\.5 </td><td colspan="1">125 </td><td colspan="1">UTS150·H·FTU·125·3P·UL </td><td colspan="2">EBS203c </td><td colspan="2">150 </td><td colspan="2">MC- 150a </td><td colspan="1">150 </td></tr>
<tr><td colspan="1">22 </td><td colspan="1">150 </td><td colspan="1">UTS150·H·FTU·150·3P·UL </td><td colspan="2">EBS203c </td><td colspan="2">175 </td><td colspan="2">MC- 185a </td><td colspan="1">185 </td></tr>
<tr><td colspan="1" rowspan="2">3상 400V 급 </td><td colspan="1">0\.4 </td><td colspan="1" rowspan="2">UTS150L </td><td colspan="1">3\.2 </td><td colspan="1">UTS150·L·MCP·3.2·3P·UL </td><td colspan="2" rowspan="2">EBS33c </td><td colspan="2" rowspan="2">5 </td><td colspan="2">MC-6a </td><td colspan="1">7 </td></tr>
<tr><td colspan="1">0\.75 </td><td colspan="1">6\.3 </td><td colspan="1">UTS150·L·MCP·6.3·3P·UL </td><td colspan="2">MC-6a </td></tr>
</table>
