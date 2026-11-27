---
title: "Auditory Intelligence Lab - Research"
layout: textlay
excerpt: "Auditory Intelligence Lab - Research"
sitemap: false
permalink: /research/
---

<div class="research-page" markdown="0">

  <div class="research-page-header">

    <h1>Research</h1>

    <div class="research-heading-line"></div>

  </div>


  <div class="research-page-layout">

    <!-- RESEARCH SIDEBAR -->

    <aside class="research-sidebar">

      <nav aria-label="Research areas">

        <h4>Research Areas</h4>

        <a href="#sound-world-model">
          <i data-lucide="audio-waveform"></i>
          <span>Sound World Model</span>
        </a>

        <a href="#speech-llm">
          <i data-lucide="brain-circuit"></i>
          <span>Speech-LLM</span>
        </a>

        <a href="#on-device-ai">
          <i data-lucide="cpu"></i>
          <span>On-device AI</span>
        </a>

        <a href="#multimodal-audio">
          <i data-lucide="audio-lines"></i>
          <span>Multimodal Audio</span>
        </a>

        <a href="#explainable-ai">
          <i data-lucide="scan-search"></i>
          <span>Explainable AI</span>
        </a>

        <a href="#speech-recognition">
          <i data-lucide="mic"></i>
          <span>Speech Recognition</span>
        </a>

      </nav>

    </aside>


    <!-- RESEARCH CONTENT -->

    <div class="research-main">


      <!-- 01. Sound World Model -->

      <section class="research-block" id="sound-world-model">


        <h2>Sound World Model for Physical AI</h2>

        <ul>
          <li>
            소리를 통해 물리 공간의 음원, 객체 및 환경을 인지하고
            공간적, 의미적 관계를 이해
          </li>

          <li>
            Sound Source Localization /
            Acoustic Scene Understanding /
            Spatial Audio Modeling
          </li>
        </ul>

        <figure>
          <img src="{{ site.baseurl }}/images/respic/sound%20world%20model.png"
               alt="Sound World Model for Physical AI"
               loading="lazy">
        </figure>

      </section>


      <!-- 02. Speech-LLM -->

      <section class="research-block" id="speech-llm">


        <h2>Speech-LLM</h2>

        <ul>
          <li>
            사전 학습된 Speech Encoder를 사용하여
            음성을 LLM의 언어 공간에 직접 정렬
          </li>

          <li>
            텍스트 변환 없이 음성 고유의 운율, 감정 정보를 활용하여
            End-to-End 추론 수행
          </li>
        </ul>

        <figure>
          <img src="{{ site.baseurl }}/images/respic/speech%20llm.png"
               alt="Speech-LLM"
               loading="lazy">
        </figure>

      </section>


      <!-- 03. On-device AI -->

      <section class="research-block" id="on-device-ai">


        <h2>On-device Speech-LLM for Physical AI</h2>

        <ul>
          <li>
            실시간 반응성과 제한된 자원을 갖는 로봇 환경에서는
            Speech-LLM의 경량화가 요구됨
          </li>

          <li>
            Speech-LLM을 경량화하여 로봇 환경에서 음성 지시를
            효율적으로 이해하고, VLA를 통해 행동을 생성
          </li>
        </ul>

        <figure>
          <img src="{{ site.baseurl }}/images/respic/on%20device.png"
               alt="On-device Speech-LLM"
               loading="lazy">
        </figure>

      </section>


      <!-- 04. Multimodal Audio -->

      <section class="research-block" id="multimodal-audio">


        <h2>Multimodal Video-to-Audio Synthesis</h2>

        <ul>
          <li>
            영상 이벤트와 정밀하게 동기화된 Foley/SFX 자동 생성
          </li>

          <li>
            Diffusion 모델 기반의 고품질 오디오 생성 기술 연구
          </li>

          <li>
            텍스트 및 시각적 의미 정보를 활용한 사운드 뉘앙스 제어
          </li>
        </ul>

        <figure>
          <img src="{{ site.baseurl }}/images/respic/multimodal.png"
               alt="Multimodal Video-to-Audio Synthesis"
               loading="lazy">

          <figcaption>
            Liu, H., Yuan, Y., Liu, X. et al.
            AudioLDM 2: Learning Holistic Audio Generation
            with Self-Supervised Pretraining.
            IEEE/ACM Transactions on Audio, Speech,
            and Language Processing 32, 2871–2883 (2024).
          </figcaption>
        </figure>

      </section>


      <!-- 05. Explainable AI -->

      <section class="research-block" id="explainable-ai">


        <h2>음성 명료도 평가 및 설명가능한 인공지능 기법 연구</h2>

        <div class="research-subsection">

          <h3>
            Explainable AI (XAI) for Digital Healthcare
            in Post-stroke Dysarthria
          </h3>

          <ul>
            <li>음향학적 자질을 이용한 말 장애 판별</li>

            <li>
              음성 인식을 이용한 말 장애 오류 유형/구간 분석
            </li>
          </ul>

          <figure>
            <img src="{{ site.baseurl }}/images/respic/음성명료도1.png"
                 alt="Speech Intelligibility Assessment"
                 loading="lazy">
          </figure>

          <figure>
            <img src="{{ site.baseurl }}/images/respic/음성명료도2.png"
                 alt="Explainable AI for Dysarthria"
                 loading="lazy">
          </figure>

        </div>


        <div class="research-subsection">

          <h3>LLM &amp; ASR for L2 Korean</h3>

          <ul>
            <li>외국인 한국어 발화자의 한국어 음성인식</li>

            <li>
              LLM을 이용한 말하기 내용/언어사용 점수 평가
            </li>
          </ul>

          <figure>
            <img src="{{ site.baseurl }}/images/respic/llm&amp;asr.png"
                 alt="LLM and ASR for L2 Korean"
                 loading="lazy">
          </figure>

        </div>

      </section>


      <!-- 06. Speech Recognition -->

      <section class="research-block" id="speech-recognition">


        <h2>End-to-End 방식의 음성인식 시스템</h2>

        <div class="research-subsection">

          <h3>E2E 방식의 한국어 음성인식 모델 연구</h3>

          <ul>
            <li>
              E2E 방식과 WFST의 결합을 통한
              인식 성능, 속도 향상
            </li>
          </ul>

          <figure>
            <img src="{{ site.baseurl }}/images/respic/e2e.png"
                 alt="End-to-End Speech Recognition"
                 loading="lazy">

            <figcaption>
              OpenAI/Whisper (2022)
            </figcaption>
          </figure>

        </div>


        <div class="research-subsection">

          <h3>Continual Learning for ASR</h3>

          <ul>
            <li>
              Continual Learning 기법을 적용하여,
              데이터가 연속적으로 추가되는 환경에서도
              안정적인 성능을 유지하는 ASR 모델 연구
            </li>
          </ul>

          <figure>
            <img src="{{ site.baseurl }}/images/respic/continual.png"
                 alt="Continual Learning for ASR"
                 loading="lazy">
          </figure>

        </div>

      </section>

    </div>

  </div>

</div>

<script>
(function () {

    const links = document.querySelectorAll('.research-sidebar a');
    const sections = document.querySelectorAll('.research-block');

    function updateActiveSection() {

        let current = sections[0].id;

        sections.forEach(function (section) {
            if (section.getBoundingClientRect().top <= 140) {
                current = section.id;
            }
        });

        links.forEach(function (link) {
            const active =
                link.getAttribute('href') === '#' + current;

            link.classList.toggle('active', active);

            if (active) {
                link.setAttribute('aria-current', 'location');
            } else {
                link.removeAttribute('aria-current');
            }
        });
    }

    window.addEventListener('scroll', updateActiveSection, {
        passive: true
    });

    window.addEventListener('resize', updateActiveSection);
    window.addEventListener('load', updateActiveSection);

    updateActiveSection();

})();
</script>
