# Omegi Instrumentation

## Description

Opentelemetry Instrumentation을 이용한 파이썬 자동 계측기 라이브러리입니다. 
Function 단위로 span을 생성하며, 분산 시스템에서의 에러 발생 시 로그 추적을 돕는 기능을 제공합니다.
사용자는 어플리케이션에서 에러가 발생할 경우 분산 시스템에서 에러 발생 경로를 파악할 수 있으며, 그 과정을 자동화 하기 위해서는 각 서비스에서 omegi-instrumentation이 활성화 되어 있어야 합니다.
