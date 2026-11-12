# ⚠️ 보안 연구용 파일 — 다운로드 및 실행 금지

## 한국어

이 저장소의 `test.exe`는 실제 사용을 위한 일반 프로그램이 아닙니다. 격리된 가상머신에서 포렌식 문제와 보안 교육 시나리오를 재현하기 위해 제작된 연구용 실행 파일입니다.

`test.exe`는 외부 서버에서 추가 실행 파일을 내려받아 Windows 임시 폴더에 저장한 뒤 실행하도록 설계되어 있습니다. 내려받은 프로그램은 시스템·계정·네트워크·프로세스 등의 정보를 수집할 수 있습니다.

**이 파일을 다운로드하거나 실행하지 마십시오.** 특히 개인 PC, 업무용 PC, 운영 서버, 실제 사용자 정보가 저장된 시스템에서는 절대로 실행하지 마십시오.

- 명시적으로 허가된 격리형 VM 실습 환경에서만 취급하십시오.
- 네트워크와 공유 폴더가 실제 환경으로 연결되지 않았는지 확인하십시오.
- 분석이 끝난 후에는 VM 스냅샷을 복원하거나 실습 환경을 폐기하십시오.
- 무단 실행, 배포 또는 제3자 시스템 대상 사용을 금지합니다.

이 저장소의 자료는 포렌식 교육 및 승인된 보안 연구 목적으로만 제공됩니다.

---

## English

The `test.exe` file in this repository is not a general-purpose application. It is a research artifact created for a forensic challenge and security-training scenario inside an isolated virtual machine.

`test.exe` is designed to download an additional executable from an external server, save it in the Windows temporary directory, and run it. The downloaded program may collect system, account, network, and process information.

**Do not download or execute this file.** Never run it on a personal computer, work computer, production server, or any system containing real user data.

- Handle it only inside an explicitly authorized and isolated VM lab.
- Confirm that the lab network and shared folders are disconnected from real environments.
- Restore the VM snapshot or dispose of the lab environment after analysis.
- Unauthorized execution, redistribution, or use against third-party systems is prohibited.

The materials in this repository are provided solely for forensic education and authorized security research.
