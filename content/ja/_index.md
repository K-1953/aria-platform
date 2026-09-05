---
title: ''
summary: 'ARIA — 防災ITのための研究基盤'
type: landing

design:
  spacing: '5rem'

sections:
  - block: markdown
    id: aria
    content:
      title: 'ARIA'
      subtitle: '防災ITのための研究基盤'
      text: |-
        **ARIA**は、災害に関わるさまざまなシミュレータ、観測機器、情報システム、解析技術を連携させるための研究基盤です。

        災害は、降雨や浸水などの自然現象だけでなく、人の避難行動、通信環境、電力、道路、情報サービスなど、多くの要素が相互に影響しながら進行します。一方で、これらを扱う技術は、それぞれ独立して発展してきました。

        ARIAでは、個々の技術を一つの巨大なシステムに作り直すのではなく、それぞれのシミュレータや実システムを生かしたまま柔軟に組み合わせ、同じ災害状況の中で協調して動作させます。

        これにより、災害現象だけでなく、その結果として生じるインフラ障害や情報サービスへの影響、人の行動まで含めて、災害時の社会をより総合的に再現・分析することを目指しています。
    design:
      columns: '1'

  - block: markdown
    id: capabilities
    content:
      title: 'ARIAでできること'
      subtitle: ''
      text: |-
        ### 災害時の複数の現象を組み合わせて再現する
        浸水、避難行動、通信環境、情報システムなど、異なるシミュレータや解析技術を連携させ、相互の影響を反映しながら災害状況を再現できます。

        ### 解析技術やシミュレータを検証する
        新しい解析手法やシミュレータをARIA上に組み込み、他の要素技術と連携させながら、その性能や妥当性を評価できます。過去の災害データや異なる条件を用いて繰り返し検証できるため、防災技術の研究開発や改良のための評価基盤として利用できます。

        ### 防災アプリや情報システムを事前に試す
        ARIA上の一部を実際のアプリやシステムに置き換えることで、通信障害や浸水などが発生する状況の中で、そのシステムがどこまで動作するか、どこで使えなくなるかを検証できます。

        ### 災害時の情報の届き方や行動への影響を調べる
        災害によるインフラ障害が、情報提供や避難行動にどのように波及するかを追跡し、サービスの停止や遅延が最終的な行動に与える影響を分析できます。
    design:
      columns: '1'

  - block: markdown
    id: research
    content:
      title: '研究テーマと成果'
      subtitle: ''
      text: |-
        ### 1. 連携基盤の開発
        異なるシミュレータ、インフラモデル、サービス、アプリ、実システムを柔軟に連携させるARIA基盤と、そのための連携手法を研究開発します。

        <div class="research-grid">
          <div class="research-output">
            <div class="research-meta"><strong>Performance Evaluation of An Orchestrator Framework for Disaster Cyber-Physical System</strong> <a href="https://scholar.google.com/scholar?hl=ja&as_sdt=0%2C5&q=Performance+Evaluation+of+An+Orchestrator+Framework+for+Disaster+Cyber-Physical+System&btnG=">Paper</a></div>
            <a class="research-image-link" href="/images/infographics/ITDRR2024_ja.png" target="_blank" rel="noopener"><img src="/images/infographics/ITDRR2024_ja.png" alt="Performance Evaluation of An Orchestrator Framework for Disaster Cyber-Physical System"></a>
          </div>

          <div class="research-output">
            <div class="research-meta"><strong>A Structured Evacuation Simulator Framework for Federation Strategy during Flood Disasters</strong> <a href="https://scholar.google.com/scholar?hl=ja&as_sdt=0%2C5&q=A+Structured+Evacuation+Simulator+Framework+for+Federation+Strategy+during+Flood+Disasters&btnG=">Paper</a></div>
            <a class="research-image-link" href="/images/infographics/ICAE1_2024_ja.png" target="_blank" rel="noopener"><img src="/images/infographics/ICAE1_2024_ja.png" alt="A Structured Evacuation Simulator Framework for Federation Strategy during Flood Disasters"></a>
          </div>
        </div>

        ---

        ### 2. 連携基盤による分析
        ARIAを用いて、災害によるインフラ、情報サービス、アプリ、人の行動への影響や、依存関係を通じた障害の波及を分析します。

        <div class="research-grid">
          <div class="research-output">
            <div class="research-meta"><strong>Power Failure Emulator for Communication Network in Disaster Situation</strong> <a href="https://scholar.google.com/scholar?hl=ja&as_sdt=0%2C5&q=Power+Failure+Emulator+for+Communication+Network+in+Disaster+Situation&btnG=">Paper</a></div>
            <a class="research-image-link" href="/images/infographics/ICAE2_2024_ja.png" target="_blank" rel="noopener"><img src="/images/infographics/ICAE2_2024_ja.png" alt="Power Failure Emulator for Communication Network in Disaster Situation"></a>
          </div>

          <div class="research-output">
            <div class="research-meta"><strong>Emotional Parameters for Evacuation Agents via Live Earthquake Stream Analysis</strong></div>
            <a class="research-image-link" href="/images/infographics/IJIS2025_ja.png" target="_blank" rel="noopener"><img src="/images/infographics/IJIS2025_ja.png" alt="Emotional Parameters for Evacuation Agents via Live Earthquake Stream Analysis"></a>
          </div>
        </div>

        ---

        ### 3. 疑似災害データ
        実験条件として利用できる災害シナリオや疑似災害データの生成手法を研究します。降雨・洪水をはじめ、他の災害への拡張も進めます。

        <div class="research-grid">
          <div class="research-output">
            <div class="research-meta"><strong>Generative Synthesis of Precipitation Radar Data for Disaster IT Testbed</strong> <a href="https://scholar.google.com/scholar?hl=ja&as_sdt=0%2C5&q=Generative+Synthesis+of+Precipitation+Radar+Data+for+Disaster+IT+Testbed&btnG=">Paper</a></div>
            <a class="research-image-link" href="/images/infographics/CDS2025_ja.png" target="_blank" rel="noopener"><img src="/images/infographics/CDS2025_ja.png" alt="Generative Synthesis of Precipitation Radar Data for Disaster IT Testbed"></a>
          </div>
        </div>
    design:
      columns: '1'

  - block: markdown
    id: members
    content:
      title: 'メンバー'
      subtitle: ''
      text: |-
        <div class="member-grid">
          <div><img class="member-photo" src="/images/members/kei-hiroi.png" alt="廣井 慧"><strong>廣井 慧</strong><br>Kei Hiroi<br><small>京都大学防災研究所<br>Disaster Prevention Research Institute,<br>Kyoto University</small></div>
          <div><img class="member-photo" src="/images/members/akihito-kohiga.png" alt="小比賀 亮仁"><strong>小比賀 亮仁</strong><br>Akihito Kohiga<br><small>同志社大学<br>Doshisha University</small></div>
          <div><img class="member-photo" src="/images/members/sho-fukaya.png" alt="深谷 将"><strong>深谷 将</strong><br>Sho Fukaya<br><small>公立諏訪東京理科大学<br>Suwa University of Science</small></div>
          <div><img class="member-photo" src="/images/members/yoichi-shinoda.png" alt="篠田 陽一"><strong>篠田 陽一</strong><br>Yoichi Shinoda<br><small>NTTドコモビジネス<br>NTT DOCOMO BUSINESS, Inc.</small></div>
        </div>
    design:
      columns: '1'

  - block: markdown
    id: project
    content:
      title: 'プロジェクト情報'
      subtitle: ''
      text: |-
        研究代表者：**廣井 慧（京都大学）**

        連絡先：**hiroi[at]dimsis.dpri.kyoto-u.ac.jp**
    design:
      columns: '1'
---