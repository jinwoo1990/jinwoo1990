# Hello, I'm Jin :bagel:

## :mountain: About Me

IBM에서 5년째 데이터 사이언티스트/컨설턴트로 근무하고 있습니다. 유통, 의료, 제조, 에너지 등 다양한 산업 분야에서 데이터 분석과 머신러닝/최적화 모델 개발, 도커와 파이썬 웹프레임워크를 활용한 어플리케이션 개발, AI 전략 컨설팅을 수행하고 있습니다. 현재 실제 비즈니스에서 작동하는 AI 어플리케이션의 End-to-end 개발/기획자를 목표로 하고 있습니다.

## :dart: Interests

- Full stack development of AI applications
- ML/DL modeling
- Optimization
- Working efficiency
- Blog writing (*[Link](https://jinwoo1990.github.io/)*)

## :books: Repositories


### :fountain_pen: Main

#### mlops-demo :pushpin:
> **Keywords**: Tensorflow | TFX | Kubeflow | TFServing | GKE | BigQuery | CloudSQL | Streamlit | Github Action *[View Source](https://github.com/jinwoo1990/mlops-demo)*

MLOps Demo repository는 분석 주제별 production 레벨의 머신러닝 시스템 코드를 포함하고 있습니다. Google MLOps Level 2 기준의 머신러닝 시스템 구현을 목표로 합니다. 구글 클라우드 기반으로 TFX와 Kubeflow를 이용해 개발을 진행하고 있습니다. 현재 기준으로 performance monitoring 부분을 제외하고 간단한 코드들로 Level 2 기준의 시스템을 구현했습니다. 프로젝트는 Zenhub와 Git Flow 브랜치 전략을 사용해 진행했습니다. 일부 모듈에 대해서는 추가적인 고도화 및 테스트가 필요합니다.

(현재 가장 중점적으로 작업하고 있는 프로젝트입니다. 프로젝트 README에 자세한 수행 내용을 작성했습니다.)

#### ml-streamlit-app
> **Keywords**: XGBoost | LightGBM | scikit-learn | Shap | Stereamlit | Flask | Docker | MongoDB | AWS S3 *[View Source](https://github.com/jinwoo1990/ml-streamlit-app)*

커스텀 코드로 작성된 모델 파이프라인 및 모델 관리 코드를 포함하고 있습니다. MongoDB를 학습 모델 메타데이터 저장소로 이용했고 S3를 모델 바이너리 저장을 위해 사용했습니다.

(머신러닝 코드보다 예외 처리, 연결 설정, 커스텀 코드 모듈화 등의 작업이 많아 진행을 중지하고 현재는 다른 프로젝트에서 오픈소스 기반의 구현을 알아보고 있습니다.)

#### ccpp-demo *[Temporary Service Demo Address](http://13.209.234.231:8501/)*
> **Keywords**: XGBoost | Keras | scikit-learn | Shap | Stereamlit | Flask | Docker *[View Source](https://github.com/jinwoo1990/ccpp-demo)*

:memo: *[Streamlit, Flask, Docker 를 활용한 머신러닝 데모 앱 만들기 (with XGBoost, Keras, Shap) - Dev Blog by Jin](https://jinwoo1990.github.io/toy-projects/ccpp-demo/)*

CCPP 데이터를 활용해 만든 전기 발전량 예측 데모 웹 어플리케이션 프로젝트입니다.

(MLflow, seldon-core, graphana 등의 오픈소스 기술들을 바탕으로 MLOps 기능을 향후 release에 추가할 예정이었습니다. 현재는 TFX와 Kubeflow 기반의 아키텍처를 고려하고 있어 보류한 상태입니다.)

---

### :book: For Blog Contents

머신러닝/딥러닝부터 데이터 분석을 활용한 시스템 구축에 필요한 백엔드/프론트엔드까지 데이터 분석을 하며 경험한 개발 주제에 대해 다룹니다. 아래에 나온 내용 외에도 리눅스, 쉘, 파이썬 등 프로젝트를 하며 정리했던 다양한 주제들을 포함하고 있습니다. *[View Blog Contents](https://jinwoo1990.github.io/)*

#### mlops-with-tensorflow

> **Keywords**: TFDV *[View Source](https://github.com/jinwoo1990/mlops-with-tensorflow)*

Production ML 시스템을 위해 필요한 여러가지 기술들에 대한 샘플 코드들을 포함하고 있습니다. 개인적으로 관련 기술들을 사용해보며 궁금하거나 중요해보이는 내용들을 다루고 있습니다.

:memo: *[TFDV skew/drift comparator metrics 알아보기 - L-Infinity Distance & Jensen-Shannon Divergence - Dev Blog by Jin](https://jinwoo1990.github.io/)*

관련 이슈: :octocat: https://github.com/tensorflow/data-validation/issues/207

(정리한 내용을 바탕으로 TFDV github issue에 답한 내용을 블로그에 옮기려 합니다.)

#### git-flow-tutorial
> **Keywords**: Git | Jira *[View Source](https://github.com/jinwoo1990/git-flow-tutorial)*

블로그 예시를 위해 작성된 Git flow 브랜치 전략과 Jira를 활용한 샘플 코드를 포함하고 있습니다.

:memo: *[Git Flow - 2. 샘플 프로젝트를 통한 사용법 예시 (How to/Tutorial) - Dev Blog by Jin](https://jinwoo1990.github.io/git/git-flow-tutorial/)*

---

### :paintbrush: Others

#### kaggle-practice
> **Keywords**: Kaggle | XGBoost | LightGBM | CatBoost | Keras | scikit-learn | Shap *[View Source](https://github.com/jinwoo1990/kaggle-practice)*

Kaggle competiton 관련 코드들을 포함하고 있습니다.

#### airbnb-clone
> **Keywords**: Django | Tailwind | AWS EC2 | AWS RDS | AWS S3 | AWS Elastic Beanstalk *[View Source](https://github.com/jinwoo1990/airbnb-clone)*

노마드 코더의 Airbnb clone coding 강의를 바탕으로 작성한 Django 클론 프로젝트입니다. 회사 프로젝트 중 PoC 단계의 코드를 시스템화해야 할 일이 생겼고, 이 때 파이썬 기반 웹 시스템에 대한 기본적인 이해를 높이기 위해 수행했습니다.

(클론 코딩 이후 사이트 구조와 mock 데이터를 바탕으로 추천, 악성 댓글 탐지 등의 머신러닝 기능들을 추가할 예정이었으나 생각보다 Django 코드나 프론트엔드 코드를 다룰 일이 많아 보류한 상태입니다.)
