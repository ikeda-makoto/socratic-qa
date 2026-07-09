# ソクラテスQA（socratic-qa）/ Maieutic AI

**Maieutic AI（AIソクラテス産婆術）** のための対話メソッドの仕様書です。
ソクラテスの産婆術（maieutics）をベースに、対話によって **相手自身の中から答えを引き出し、定着させる**ことを目的とします。

「答えを教える」のではなく、「答えが生まれる余白と構造をつくる」ことを核とします。
問い（発見）と知識（固定）を意図的に切り替えながら、ユーザー自身の洞察を
最も深く受け取れる形（生成効果）で対話を進めます。

🇬🇧 **English readers:** Full English translations are available —
[README (English section below)](#english) ｜ [`concept-en.md`](./concept-en.md) ｜ [`socratic-qa-en.md`](./socratic-qa-en.md)

---

## この文書について

- **作者**：原石工房（ゆう）/ Maieutic AI
- **note**：<https://note.com/genseki_kobo>
- **位置づけ**：継続的に改訂している「生きたドキュメント」です。
  バージョン履歴と設計の理由は、本文末尾の改善ログに記録しています。
- **正本**：このリポジトリの `socratic-qa.md` が常に最新版です。
- **方法論の原理・独自性・考案の経緯**：[`concept.md`](./concept.md) にまとめています。
  なぜこの方法が効くのか（①〜⑤の循環）、科学的裏付け、既存手法との違い、考案の時系列を記録し、
  認定タイムスタンプ（2026年6月）で起源を固定しています。

---

## ファイル構成

- [`socratic-qa.md`](./socratic-qa.md) — 対話メソッドの仕様書（正本・常に最新版）。AIに実行させるための指示書。
- [`socratic-qa-en.md`](./socratic-qa-en.md) — 仕様書の英語版（参考訳）。
- [`concept.md`](./concept.md) — 考案記録。方法論の原理（①〜⑤の循環）、科学的裏付け、独自性、考案の経緯。
- [`concept-en.md`](./concept-en.md) — 考案記録の英語版（参考訳）。
- `socratic-qa-cycle.jpg` — ①〜⑤の循環図。
- `ソクラテスQA_考案記録20260627.pdf` — 考案記録に認定タイムスタンプ（総務大臣認定事業者）を付与したPDF。起源の証拠。
- [`LICENSE.md`](./LICENSE.md) — ライセンス（CC BY 4.0）。

※ 英語版はいずれも参考訳であり、日本語原本が正本です。

---

## ライセンス

このメソッドは **CC BY 4.0** の下で公開しています。
読むこと・使うこと・広めることを歓迎します。
ただし、利用の際は **作者（原石工房（ゆう）/ Maieutic AI）** を明示してください。
詳しくは [LICENSE.md](./LICENSE.md) をご覧ください。

なお、このメソッドは人の主体性を回復するために作られたものです。
人を操作・支配・依存させる目的での利用は、作者の意図に反します
（詳細はライセンス内に記載）。

---

## English

**socratic-qa** is a dialogue methodology specification for **Maieutic AI** —
AI-assisted Socratic midwifery. Based on the Socratic method of *maieutics*
(the "midwifery" of ideas), it helps draw out and settle answers **from within
the person**, rather than teaching answers directly.

Where a typical AI answers questions, Socratic QA inverts the flow:

1. **Ask into the blind spot** — a question opens an "information gap" the person had not noticed.
2. **Speak it aloud** — the person articulates their thinking in their own words (the generation effect).
3. **Discover the gap** — in explaining, they notice what they don't yet know; craving builds.
4. **Deliver knowledge at the peak** — only at the peak of curiosity does the AI hand over the precise knowledge that person needs.
5. **Intrinsic motivation** — because every step was their own, the person wants to continue.

The goal is not knowledge acquisition but **self-acceptance and lasting inner
transformation** — grounded in information-gap theory (Loewenstein, 1994), the
generation effect (Slamecka & Graf, 1978), curiosity–memory neuroscience
(Gruber et al., 2014), and self-determination theory (Deci & Ryan).

The specification is a **living document**: it is revised through real coaching
sessions, and every revision — including honest records of failure — is logged
with its reasoning in the improvement log at the end of the spec.

### Documents in English

- [`socratic-qa-en.md`](./socratic-qa-en.md) — the full methodology specification
  (fundamental stance, the two modes, STEP 0–6, safety devices, case handling,
  and the complete improvement log v1.0–v2.2).
- [`concept-en.md`](./concept-en.md) — the record of conception: the five
  components and their scientific grounding, an honest analysis of what is
  original and what is not, and the timeline of conception. The Japanese
  original carries a certified timestamp (June 2026, issued via a timestamp
  authority accredited by Japan's Minister of Internal Affairs and
  Communications) fixing its origin as a verifiable record.

Both are reference translations; the Japanese originals are authoritative.

- **Author**: Genseki-kobo (Yu) / Maieutic AI — <https://note.com/genseki_kobo>
- **License**: CC BY 4.0 — see [LICENSE.md](./LICENSE.md). This method was
  created to restore human agency; using it to manipulate, dominate, or create
  dependency in people is contrary to the author's intent.
