# ForgeVM MVP 공개 기록 | ForgeVM MVP Publication Record

> **기록 상태 | Record status:** Published  
> **문서 ID | Document ID:** `FVM-MVP-ROADMAP-DP-1.0`  
> **최초 공개일 | First publication date:** 2026-07-30 KST  
> **권리자 | Rights holder:** Facta-Leopard

## 공개 대상 | Intended public material

이 저장소에서 기술적 내용을 공개하는 본문은 `README.md`의 ForgeVM MVP
로드맵 M0–M13뿐이다. `LICENSE`, 이 기록과 `SHA256SUMS`는 권리, 공개
상태와 무결성을 설명하는 부속 자료다.

The only substantive technical publication in this repository is the ForgeVM
MVP M0–M13 roadmap in `README.md`. `LICENSE`, this record, and `SHA256SUMS`
are ancillary records of rights, publication state, and integrity.

공개하지 않는 범위:

Excluded from publication:

- 전체 제품 및 포스트 MVP 로드맵  
  full-product and post-MVP roadmaps;
- 내부 개발지시서, 운영 문서, 위험 등록부와 로컬 경로  
  internal directives, operating documents, risk registers, and local paths;
- source code, build artifact, credential, signing identity와 third-party
  binary  
  source code, build artifacts, credentials, signing identities, and
  third-party binaries;
- 별도 비공개 특허 검토 체크리스트와 그 안의 판단  
  the separate confidential patent-screening checklist and its decisions.

## 공개본 fingerprint | Publication fingerprint

공개 file hash는 `SHA256SUMS`에 기록한다. Hash는 공개된 content를
식별하고, GitHub commit history는 해당 content가 공개된 시점을
기록한다.

Public file hashes are recorded in `SHA256SUMS`. The hashes identify the
published content, while GitHub commit history records when that content
became public.

## 공개 metadata | Publication metadata

| Field | Recorded value |
|---|---|
| Publication decision | `PUBLISHED` |
| Public repository URL | `https://github.com/Facta-Leopard/ForgeVM` |
| First public commit SHA | `32e49390d48082f2d8e9d2290ceda9e063850db9` |
| Initial commit timestamp (UTC) | `2026-07-29T19:29:18Z` |
| First public accessibility verified (UTC) | `2026-07-29T20:13:21Z` |
| First public accessibility verified (KST) | `2026-07-30T05:13:21+09:00` |
| Annotated release tag | `mvp-roadmap-v1.0` |
| GitHub release URL | `https://github.com/Facta-Leopard/ForgeVM/releases/tag/mvp-roadmap-v1.0` |
| Independent archive URL and timestamp | `NOT_CREATED` |
| Published README SHA-256 | `0714c4e2d5320435b282d09124c0b1a0885e46a2e3984cf20a9a51ab8f4698ba` |
| Published LICENSE SHA-256 | `7b45ac8eb414d82235fc0888c7ea665feff56a0c4e12dc69943d06c7f974c749` |

## 실행한 공개 절차 | Executed publication procedure

1. 별도 비공개 체크리스트에서 공개 후보를 분리하고 소유자가 공개를
   명시적으로 승인했다.  
   Confirm through the separate confidential checklist that no unresolved
   patent-first candidate remains, then obtain explicit owner approval.
2. `README.md`의 status와 document ID를 published version으로 바꾸고
   공개 시각을 UTC와 KST로 함께 기록한다.  
   Change the `README.md` status and document ID to the published version and
   record the publication time in both UTC and KST.
3. 모든 공개 파일의 SHA-256을 다시 계산하고 `SHA256SUMS`를 갱신한다.  
   Recompute SHA-256 for every public file and update `SHA256SUMS`.
4. GitHub 공개 저장소의 first commit으로 게시하고 annotated tag와
   release를 만들었다.  
   Publish as the first commit of a public GitHub repository and create an
   annotated tag and release.
5. public URL, commit SHA, tag, release와 timestamp를 이 표에 기록한
   metadata commit을 만든다. 최초 공개본은 first commit과 release로
   그대로 보존한다.  
   Record the public URL, commit SHA, tag, release, and timestamp here in a
   metadata commit. Preserve the first publication unchanged as the initial
   commit and release.
6. 독립적인 timestamped archive는 아직 만들지 않았으며, 만들 경우 같은
   release를 보존하고 URL을 위 표에 기록한다.  
   Where practical, preserve the same release file in an independent
   timestamped archive and record its URL.

## 증명 범위 | Evidentiary boundary

GitHub의 commit history와 release는 공개 시점과 내용을 보여주는 유용한
증거가 될 수 있지만, 특정 관할권의 특허 심사나 분쟁 결과를 보장하지
않는다. 공개된 내용이 충분한 선행기술인지 여부는 실제 문서 내용,
접근 가능성, 공개일과 적용 법률에 따라 판단된다.

GitHub commit history and releases can provide useful evidence of what was
publicly accessible and when, but they do not guarantee the result of a patent
examination or dispute in any jurisdiction. Whether the disclosure qualifies
as sufficient prior art depends on the actual content, public accessibility,
publication date, and applicable law.
