<style>
    /* 전체 테이블 기본 스타일 */
    table {
        width: 100%;
        border-collapse: collapse;
        margin-bottom: 20px;
    }
    th, td {
        border: 1px solid #ddd;
        padding: 8px;
        text-align: left;
        vertical-align: top;
    }
    th {
        background-color: #f2f2f2;
    }
    /* 우선순위 아이콘 색상 */
    .priority-1 { color: #FF4500; } /* 🔥 */
    .priority-2 { color: #FFD700; } /* ⭐ */
    .priority-3 { color: #ADD8E6; } /* 💡 */
    .priority-selected { color: #00BFFF; } /* 🎯 */

    /* 특화 포인트 목록 스타일 (ul 태그 내부) */
    .point-list ul {
        list-style: none; /* 기본 블릿 제거 */
        padding-left: 0;
        margin-top: 0;
        margin-bottom: 0;
    }
    .point-list li {
        margin-bottom: 5px;
        font-weight: bold;
    }
</style>

# Jay 맞춤 구글 스터디 플랜 및 추천표

## 1. 스터디 플랜
<table>
    <thead>
        <tr>
            <th>우선순위</th>
            <th>과정명</th>
            <th>학습 목표</th>
            <th>핵심 내용</th>
            <th>뱃지 종류</th>
            <th>적합 판단 이유</th>
            <th>예상 크레딧</th>
            <th>합</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class="priority-1" rowspan="3">🔥 1순위</td>
            <td>Generative AI Fundamentals</td>
            <td rowspan="3">핵심 기반 다지기</td>
            <td>AI 기초 다지기</td>
            <td>Completion Badge</td>
            <td>개념 중심, Course 형태로 충분한 이해 가능</td>
            <td>30</td>
            <td rowspan="3">75~85</td>
        </tr>
        <tr>
            <td>Prompt Design in Vertex AI</td>
            <td>프롬프트 전문가 되기</td>
            <td>Skill Badge</td>
            <td><strong>현 최대 관심사</strong><br>ChatGPT 경험 활용</td>
            <td>10~15</td>
        </tr>
        <tr>
            <td>Cloud Digital Leader</td>
            <td>풀스택 클라우드 기초</td>
            <td>Learning Path</td>
            <td>FE 개발자에게 필요한 클라우드 기초</td>
            <td>35~40</td>
        </tr>
        <tr>
            <td class="priority-2" rowspan="2">⭐ 2순위</td>
            <td>Explore Generative AI with Gemini</td>
            <td rowspan="2">기술 스택 확장</td>
            <td>최신 AI 모델 실습</td>
            <td>Skill Badge</td>
            <td>OpenAI API<br> → <strong>Gemini</strong>로 기술 스택 확장</td>
            <td>20~25</td>
            <td rowspan="2">45~55</td>
        </tr>
        <tr>
            <td>Google Cloud Computing Foundations</td>
            <td>Google Cloud 전반 기초</td>
            <td>Completion Badge</td>
            <td>개념 중심, Time limit 없음</td>
            <td>25~30</td>
        </tr>
        <tr>
            <td class="priority-3" rowspan="2">💡 3순위</td>
            <td>Responsible AI for Developers</td>
            <td rowspan="2">고급 개념 학습</td>
            <td>윤리적 AI 개발</td>
            <td>Completion Badge</td>
            <td>개념 중심, 실무 적용 가능한 중요 지식</td>
            <td>15~20</td>
            <td rowspan="2">35~45</td>
        </tr>
        <tr>
            <td>Machine Learning in the Enterprise</td>
            <td>기업 환경 ML 활용</td>
            <td>Completion Badge</td>
            <td><storng>LangChain</strong> 준비, 실무 개념 학습</td>
            <td>20~25</td>
        </tr>
        <tr>
            <td class="priority-selected">🎯 선택</td>
            <td>Build Real World AI Applications</td>
            <td>실전 도전</td>
            <td>실제 AI 앱 구축</td>
            <td>Skill Badge</td>
            <td>AI-DB 융합 경험 활용 (도전적)</td>
            <td>25~30</td>
            <td>25~30</td>
        </tr>
    </tbody>
</table>

## 2. 추천 학습 순서 (208크레딧 최대 활용)
<table>
    <thead>
        <tr>
            <th>단계</th>
            <th>포함 과정</th>
            <th>총 크레딧</th>
            <th>학습 목표</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1단계</td>
            <td><strong>Generative AI Fundamentals + Prompt Design + Cloud Digital Leader</storn></td>
            <td>75~85 크레딧</td>
            <td>핵심 기반 다지기</td>
        </tr>
        <tr>
            <td>2단계</td>
            <td><storng>Explore Generative AI + Google Cloud Foundations</storng></td>
            <td>45~55 크레딧</td>
            <td>기술 스택 확장</td>
        </tr>
        <tr>
            <td>3단계</td>
            <td><storng>Responsible AI + Machine Learning Enterprise</storng></td>
            <td>35~45 크레딧</td>
            <td>고급 개념 학습</td>
        </tr>
        <tr>
            <td>선택단계</td>
            <td><storng>Build Real World AI Applications</storng></td>
            <td>25~30 크레딧</td>
            <td>실전 도전</td>
        </tr>
        <tr>
            <td>총합</td>
            <td>전체 8개 과정</td>
            <td>180~215 크레딧</td>
            <td>완벽한 AI 전문가</td>
        </tr>
    </tbody>
</table>

## 3. 특화 포인트
<table>
    <tr>
        <td class="point-list">
            <ul>
                <li>✅ 프롬프트 엔지니어링 집중 : 1순위 과정들이 모두 관련</li>
                <li>✅ LangChain 준비 : Google Cloud 기초부터 체계적 학습</li>
                <li>✅ 개념 학습 위주 : Time limit 없는 Course 방식 우선</li>
                <li>✅ DB 부담 제거 : 약점 영역 피하고 강점 살리기</li>
                <li>✅ 풀스택 기초 : FE 개발자에게 필요한 클라우드 지식</li>
            </ul>
        </td>
    </tr>
</table>

<h2>4. 예상 수료 성과</h2>
<table>
    <thead>
        <tr>
            <th>구분</th>
            <th>개수</th>
            <th>기념품</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Skill Badge</td>
            <td>3~4개</td>
            <td>스티커 + 텀블러</td>
        </tr>
        <tr>
            <td>Completion Badge</td>
            <td>4~5개</td>
            <td>(위와 동일)</td>
        </tr>
        <tr>
            <td>총 배지 수</td>
            <td>7~9개</td>
            <td>+ 노트북파우치 가능</td>
        </tr>
    </tbody>
</table>

<h2>5. Course vs Lab 선택 기준</h2>
<table>
    <thead>
        <tr>
            <th>방식</th>
            <th>특징</th>
            <th>적합성</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Course/Learning Path</td>
            <td>Time limit 없음, 개념 중심, 체계적 학습</td>
            <td>✅</td>
        </tr>
        <tr>
            <td>단일 Lab</td>
            <td>Time limit 있음, 급하게 따라하기</td>
            <td>❌</td>
        </tr>
    </tbody>
</table>