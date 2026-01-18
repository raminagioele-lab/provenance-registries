# Identifier Specification v1 (HOR / AIPR / TLR)

## HOR
Canonical format:
hor:1:sha256-<64hex>:<issuer_id>

Example:
hor:1:sha256-aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa:hor-registry

## AIPR
Canonical format:
aipr:1:<model_namespace>:sha256-<64hex>

Example:
aipr:1:openai.gpt-4o:sha256-bbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbb

## TLR
Canonical format:
tlr:<LABEL_CODE>:<scope>:<version>

Example:
tlr:HUMAN_ONLY:content:1
