---
title: "예외 코드"
date: 2025-04-04
categories: ["jekyll", "markdown"]
---

| Code  | HTTP Status                | Message                                         |
|-------|----------------------------|-------------------------------------------------|
| C_001 | 400 BAD_REQUEST            | 요청 데이터를 모두 올바르게 입력했는지 확인해 주세요. |
| C_002 | 400 BAD_REQUEST            | 요청 데이터의 타입이 올바르지 않습니다.         |
| C_003 | 409 CONFLICT               | 요청 데이터의 값이 올바르지 않습니다.          |
| C_004 | 415 UNSUPPORTED_MEDIA_TYPE | 지원되지 않는 미디어 타입입니다.              |
| C_005 | 413 PAYLOAD_TOO_LARGE      | 요청 데이터의 크기가 너무 큽니다.             |
| C_006 | 400 BAD_REQUEST            | 요청 헤더의 content type을 확인해 주세요.     |
| S_001 | 500 INTERNAL_SERVER_ERROR  | 서버에 오류가 발생했습니다.                   |
| S_002 | 500 INTERNAL_SERVER_ERROR  | 요청 데이터 처리에 오류가 발생했습니다.       |
| S_003 | 500 INTERNAL_SERVER_ERROR  | 인증 처리에 오류가 발생했습니다.             |
| A_001 | 409 CONFLICT               | 이미 가입된 회원입니다.                      |
| A_002 | 409 CONFLICT               | 이미 존재하는 닉네임입니다.                  |
| A_003 | 403 FORBIDDEN              | 접근이 허용되지 않은 사용자입니다.           |
| A_004 | 403 FORBIDDEN              | 비밀번호를 다시 확인해 주세요.               |
| M_001 | 404 NOT_FOUND              | 회원 정보를 찾을 수 없습니다.               |
| M_002 | 400 BAD_REQUEST            | 새로운 비밀번호를 입력해 주세요.             |
| M_003 | 400 BAD_REQUEST            | 새로운 닉네임을 입력해 주세요.               |
