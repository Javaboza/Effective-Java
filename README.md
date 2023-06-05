# Effective-Java

- [이펙티브 자바 Effective Java 3/E](http://www.yes24.com/Product/Goods/65551284)

## 👋 member 
<table>
  <tr>
    <td align="center"><a href="https://github.com/yess98"><img src="https://avatars.githubusercontent.com/yess98" width="150px;" alt="">
    <td align="center"><a href="https://github.com/pushedrumex"><img src="https://avatars.githubusercontent.com/pushedrumex" width="150px;" alt="">
    <td align="center"><a href="https://github.com/june1010"><img src="https://avatars.githubusercontent.com/june1010" width="150px;" alt="">
    </td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/yess98"><b>양은서</b></td>
    <td align="center"><a href="https://github.com/pushedrumex"><b>김민정</b></td>
    <td align="center"><a href="https://github.com/june1010"><b>정석준</b></td>
  </tr>
</table>
        
## 🔏 Rule

1. 아이템 개수
    - 매주 각자 2개
2. 일정
    - Google meet 온라인
    - 매주 금요일 21:00 ~ 23:30
3. 스터디 방식
    - 매주 item 총 6개씩 진행
    - 각자 2개의 item을 맡아 학습
    - 본인의 item이 아니더라도 학습 필수
    - 본인이 맡은 item 공부 및 정리 후 발표

## 👨🏻‍💻Process

1. 서적을 보고 자유롭게 정리
2. 본인 이름의 branch 생성 후 커밋
3. 발표 전까지 정리한 내용 `Pull Request`
4. 발표&질문 끝나면 `Approve`

## 📚 Items 진행 일정

<table class="waffle" cellspacing="0" cellpadding="0">
    <thead>
    <tr>
        <th style="width:5%;" class="row-header freezebar-origin-ltr"></th>
        <th id="32334081C0" style="width:15%;" class="column-headers-background">item</th>
        <th id="32334081C2" style="width:50%;" class="column-headers-background">title</th>
        <th id="32334081C3" style="width:20%;" class="column-headers-background">발표</th>
    </tr>
    </thead>
    <tbody>
    <tr style="height: 20px">
        <th id="32334081R0" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">1</div>
        </th>
        <td class="s0" dir="ltr" rowspan="9">2장<br>객체 생성과 파괴</td>
        <td class="s2" dir="ltr">생성자 대신 정적 팩터리 메서드를 고려하라</td>
        <td class="s3" dir="ltr">은서</td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R1" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">2</div>
        </th>
        <td class="s2" dir="ltr">생성자에 매개변수가 많다면 빌더를 고려하라</td>
        <td class="s3" dir="ltr">은서</td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R2" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">3</div>
        </th>
        <td class="s2" dir="ltr">private 생성자나 열거 타입으로 싱글터임을 보증하라</td>
        <td class="s3" dir="ltr">민정</td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R3" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">4</div>
        </th>
        <td class="s2" dir="ltr">인스턴스화를 막으려거든 private 생성자를 사용하라</td>
        <td class="s3" dir="ltr">민정</td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R4" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">5</div>
        </th>
        <td class="s2" dir="ltr">자원을 직접 명시하지 말고 의존 객체 주입을 사용하라</td>
        <td class="s3" dir="ltr">석준</td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R5" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">6</div>
        </th>
        <td class="s2" dir="ltr">불필요한 객체 생성을 피하라</td>
        <td class="s3" dir="ltr">석준</td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R6" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">7</div>
        </th>
        <td class="s2" dir="ltr">다 쓴 객체 참조를 해제하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R7" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">8</div>
        </th>
        <td class="s2" dir="ltr">finalizer와 cleaner 사용을 피하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R8" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">9</div>
        </th>
        <td class="s2" dir="ltr">try-finally보다는 try-with-resources를 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R9" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">10</div>
        </th>
        <td class="s0" dir="ltr" rowspan="5">3장<br>모든 객체의 공통 메서드</td>
        <td class="s2" dir="ltr">equals는 일반 규약을 지켜 재정의하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R10" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">11</div>
        </th>
        <td class="s2" dir="ltr">equals를 재정의하려거든 hashCode도 재정의하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R11" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">12</div>
        </th>
        <td class="s2" dir="ltr">toString을 재정의하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R12" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">13</div>
        </th>
        <td class="s2" dir="ltr">clone 재정의는 주의해서 진행하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R13" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">14</div>
        </th>
        <td class="s2" dir="ltr">Comparable을 구현할지 고려하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R14" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">15</div>
        </th>
        <td class="s0" dir="ltr" rowspan="11">4장<br>클래스와 인터페이스</td>
        <td class="s2" dir="ltr">클래스와 멤버의 접근 권한을 최소화하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R15" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">16</div>
        </th>
        <td class="s2" dir="ltr">public 클래스에서는 public 필드가 아닌 접근자 메서드를 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R16" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">17</div>
        </th>
        <td class="s2" dir="ltr">변경 가능성을 최소화하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R17" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">18</div>
        </th>
        <td class="s2" dir="ltr">상속보다는 컴포지션을 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R18" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">19</div>
        </th>
        <td class="s2" dir="ltr">상속을 고려해 설계하고 문서화하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R19" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">20</div>
        </th>
        <td class="s2" dir="ltr">추상 클래스보다는 인터페이스를 우선하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R20" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">21</div>
        </th>
        <td class="s2" dir="ltr">인터페이스는 구현하는 쪽을 생각해 설계하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R21" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">22</div>
        </th>
        <td class="s2" dir="ltr">인터페이스는 타입을 정의하는 용도로만 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R22" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">23</div>
        </th>
        <td class="s2" dir="ltr">태그 달린 클래스보다는 클래스 계층구조를 활용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R23" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">24</div>
        </th>
        <td class="s2" dir="ltr">멤버 클래스는 되도록 static 으로 만들라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R24" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">25</div>
        </th>
        <td class="s2" dir="ltr">톱레벨 클래스는 한 파일에 하나만 담으라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R25" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">26</div>
        </th>
        <td class="s0" dir="ltr" rowspan="8">5장<br>제네릭</td>
        <td class="s2" dir="ltr">로 타입은 사용하지 말라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R26" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">27</div>
        </th>
        <td class="s2" dir="ltr">비검사 경고를 제거하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R27" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">28</div>
        </th>
        <td class="s2" dir="ltr">배열보다는 리스트를 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R28" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">29</div>
        </th>
        <td class="s2" dir="ltr">이왕이면 제네릭 타입으로 만들라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R29" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">30</div>
        </th>
        <td class="s2" dir="ltr">이왕이면 제네릭 메서드로 만들라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R30" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">31</div>
        </th>
        <td class="s2" dir="ltr">한정적 와일드카드를 사용해 API 유연성을 높이라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R31" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">32</div>
        </th>
        <td class="s2" dir="ltr">제네릭과 가변인수를 함께 쓸 때는 신중하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R32" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">33</div>
        </th>
        <td class="s2" dir="ltr">타입안정 이종 컨테이너를 고려하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R33" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">34</div>
        </th>
        <td class="s0" dir="ltr" rowspan="8">6장<br>열거 타입과 애너테이션</td>
        <td class="s2" dir="ltr"> int 상수 대신 열거 타입을 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R34" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">35</div>
        </th>
        <td class="s2" dir="ltr">ordinal 메소드 대신 인스턴스 필드를 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R35" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">36</div>
        </th>
        <td class="s2" dir="ltr">비트 필드 대신 EnumSet을 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R36" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">37</div>
        </th>
        <td class="s2" dir="ltr">ordinal 인덱싱 대신 EnumMap을 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R37" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">38</div>
        </th>
        <td class="s2" dir="ltr">확장할 수 있는 열거 타입이 필요하면 인터페이스를 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R38" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">39</div>
        </th>
        <td class="s2" dir="ltr">명명 패턴보다 Annotation을 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R39" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">40</div>
        </th>
        <td class="s2" dir="ltr">@Override 애너테이션을 일관되게 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R40" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">41</div>
        </th>
        <td class="s2" dir="ltr">정의하려는 것이 타입이라면 마커 인터페이스를 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R41" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">42</div>
        </th>
        <td class="s0" dir="ltr" rowspan="7">7장<br>람다와 스트림</td>
        <td class="s5" dir="ltr">익명 클래스보다 람다를 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R42" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">43</div>
        </th>
        <td class="s2" dir="ltr">람다보다는 메서드 참조를 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R43" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">44</div>
        </th>
        <td class="s2" dir="ltr">표준 함수형 인터페이스를 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R44" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">45</div>
        </th>
        <td class="s2" dir="ltr">스트림은 주의해서 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R45" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">46</div>
        </th>
        <td class="s2" dir="ltr">스트림에서는 부작용 없는 함수를 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R46" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">47</div>
        </th>
        <td class="s2" dir="ltr">반환 타입으로는 스트림보다 컬렉션이 낫다</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R47" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">48</div>
        </th>
        <td class="s5" dir="ltr">스트림 병렬화는 주의해서 사용하라</td>
        <td class="s6" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R48" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">49</div>
        </th>
        <td class="s0" dir="ltr" rowspan="8">8장<br>메서드</td>
        <td class="s2" dir="ltr">매개변수가 유효한지 검사하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R49" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">50</div>
        </th>
        <td class="s2" dir="ltr">적시에 방어적 복사본을 만들라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R50" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">51</div>
        </th>
        <td class="s2" dir="ltr">메서드 시그니처를 신중히 설계하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R51" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">52</div>
        </th>
        <td class="s2" dir="ltr">다중정의는 신중히 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R52" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">53</div>
        </th>
        <td class="s2" dir="ltr">가변인수는 신중히 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R53" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">54</div>
        </th>
        <td class="s5" dir="ltr">null 이 아닌, 빈 컬렉션이나 배열을 반환하라</td>
        <td class="s6" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R54" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">55</div>
        </th>
        <td class="s2" dir="ltr">옵셔널 반환은 신중히 해라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R55" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">56</div>
        </th>
        <td class="s2" dir="ltr">공개된 API 요소에는 항상 문서화 주석을 작성하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R56" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">57</div>
        </th>
        <td class="s0" dir="ltr" rowspan="12">9장<br>일반적인 프로그래밍 원칙</td>
        <td class="s2" dir="ltr">지역변수의 범위를 최소화하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R57" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">58</div>
        </th>
        <td class="s2" dir="ltr">전통적 for 문 보다는 for-each 문을 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R58" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">59</div>
        </th>
        <td class="s2" dir="ltr">라이브러리를 익히고 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R59" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">60</div>
        </th>
        <td class="s5" dir="ltr">정확한 답이 필요하다면 float와 double은 피하라</td>
        <td class="s6" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R60" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">61</div>
        </th>
        <td class="s2" dir="ltr">박싱된 기본 타입보다는 기본 타입을 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R61" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">62</div>
        </th>
        <td class="s2" dir="ltr">다른 타입이 적절하다면 문자열 사용을 피하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R62" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">63</div>
        </th>
        <td class="s2" dir="ltr">문자열 연결은 느리니 주의하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R63" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">64</div>
        </th>
        <td class="s2" dir="ltr">객체는 인터페이스를 사용해 참조하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R64" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">65</div>
        </th>
        <td class="s2" dir="ltr">리플렉션보다는 인터페이스를 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R65" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">66</div>
        </th>
        <td class="s5" dir="ltr">네이티브 메서드는 신중히 사용하라</td>
        <td class="s6" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R66" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">67</div>
        </th>
        <td class="s2" dir="ltr">최적화는 신중히 하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R67" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">68</div>
        </th>
        <td class="s2" dir="ltr">일반적으로 통용되는 명명 규칙을 따르라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R68" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">69</div>
        </th>
        <td class="s0" dir="ltr" rowspan="9">10장<br>예외</td>
        <td class="s2" dir="ltr">예외는 진짜 예외 상황에만 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R69" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">70</div>
        </th>
        <td class="s2" dir="ltr">복구할 수 있는 상황에는 검사 예외를, 프로그래밍 오류에는 런타임 예외를 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R70" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">71</div>
        </th>
        <td class="s2" dir="ltr">필요 없는 검사 예외 사용은 피하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R71" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">72</div>
        </th>
        <td class="s5" dir="ltr">표준 예외를 사용하라</td>
        <td class="s6" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R72" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">73</div>
        </th>
        <td class="s2" dir="ltr">추상화 수준에 맞는 예외를 던지라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R73" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">74</div>
        </th>
        <td class="s2" dir="ltr">메서드가 던지는 모든 예외를 문서화하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R74" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">75</div>
        </th>
        <td class="s2" dir="ltr">예외의 상세 메시지에 실패 관련 정보를 담으라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R75" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">76</div>
        </th>
        <td class="s2" dir="ltr">가능한 한 실패 원자적으로 만들라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R76" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">77</div>
        </th>
        <td class="s5" dir="ltr">예외를 무시하지 말라</td>
        <td class="s6" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R77" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">78</div>
        </th>
        <td class="s0" dir="ltr" rowspan="7">11장<br>동시성</td>
        <td class="s2" dir="ltr">공유 중인 가변 데이터는 동기화해 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R78" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">79</div>
        </th>
        <td class="s2" dir="ltr">과도한 동기화는 피하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R79" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">80</div>
        </th>
        <td class="s2" dir="ltr">스레드보다는 실행자, 태스크, 스트림을 애용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R80" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">81</div>
        </th>
        <td class="s2" dir="ltr">wait와 notify보다는 동시성 유틸리티를 애용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R81" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">82</div>
        </th>
        <td class="s5" dir="ltr">스레드 안전성 수준을 문서화하라</td>
        <td class="s6" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R82" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">83</div>
        </th>
        <td class="s2" dir="ltr">초기화는 신중히 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R83" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">84</div>
        </th>
        <td class="s2" dir="ltr">프로그램의 동작을 스레드 스케줄러에 기대지 말라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R84" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">85</div>
        </th>
        <td class="s7" dir="ltr" rowspan="6">12장<br>직렬화</td>
        <td class="s2" dir="ltr">자바 직렬화의 대안을 찾으라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R85" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">86</div>
        </th>
        <td class="s5" dir="ltr">Serializable을 구현할지는 신중히 결정하라</td>
        <td class="s6" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R86" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">87</div>
        </th>
        <td class="s2" dir="ltr">커스텀 직렬화 형태를 고려해보라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R87" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">88</div>
        </th>
        <td class="s2" dir="ltr">readObject 메서드는 방어적으로 작성하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R88" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">89</div>
        </th>
        <td class="s2" dir="ltr">인스턴스 수를 통제해야 한다면 readResolve보다는 열거 타입을 사용하라</td>
        <td class="s3" dir="ltr"></td>
    </tr>
    <tr style="height: 20px">
        <th id="32334081R89" style="height: 20px;" class="row-headers-background">
            <div class="row-header-wrapper" style="line-height: 20px">90</div>
        </th>
        <td class="s8" dir="ltr">직렬화된 인스턴스 대신 직렬화 프록시 사용을 검토하라</td>
        <td class="s9" dir="ltr"></td>
    </tr>
    </tbody>
</table>
