# Mythos Atlas — Greek Myth & Ancient Epic

한국어/English로 읽는 고대 신화·서사 장기 연재 프로젝트입니다. GitHub 저장소 자체가 아니라 GitHub Pages 정적 웹사이트를 독자용 인터페이스로 사용하도록 설계했습니다.

## 전체 스토리 라인

1. Chaos — 세계 이전에는 무엇이 있었나
2. Gaia, Tartarus, Eros — 최초의 존재들
3. Gaia & Uranus — 대지와 하늘
4. Titans, Cyclopes, Hecatoncheires
5. Cronus overthrows Uranus
6. Cronus' age and the Golden Race
7. Birth of Zeus
8. Titanomachy
9. Zeus, Poseidon and Hades divide the cosmos
10. Humans — when and why do they appear?
11. Prometheus and sacrifice
12. Theft of fire
13. Pandora
14. Five Ages of Humanity
15. Lycaon and human corruption
16. Deucalion's Flood — compared with Noah, Atrahasis and Gilgamesh
17. Humanity after the Flood
18. Perseus and Medusa
19. Heracles and the Twelve Labors
20. Jason and the Argonauts
21. Theseus, Minos and the Minotaur
22. Oedipus and Thebes
23. The Theban Wars and the human-reduction motif
24. Thetis' wedding, the golden apple and Paris
25. Helen, the Greek coalition and the Cypria
26. The first nine years of the Trojan War
27. The Iliad
28. Achilles' death, the Trojan Horse and the Sack of Troy
29. The Odyssey
30. The Telegony and the death of Odysseus
31. Trojan survivors
32. Andromache, Helenus and Neoptolemus
33. Aeneas escapes Troy
34. Aeneas' Mediterranean wanderings
35. Dido and Carthage
36. Aeneas in the Underworld
37. War in Latium
38. Alba Longa and the post-Aeneas dynasties
39. Romulus and Remus
40. Foundation of Rome
41. Early Roman foundation legends
42. The Roman kings
43. Where myth, legend and history begin to separate

## Evidence grades

- **[A]** Surviving ancient primary text or artifact directly attests the claim.
- **[B]** A lost ancient work is known through ancient quotation, fragment or summary.
- **[C]** Later ancient/medieval tradition.
- **[D]** Modern scholarly interpretation, reconstruction or hypothesis.

## Editorial policy

Each installment is written as readable narrative prose, but literary presentation must not be confused with evidence. Greek traditions are compared with Mesopotamian, Egyptian, Hurrian/Hittite, Hebrew/Biblical and later Roman traditions where relevant. Similarity alone is never treated as proof of borrowing; textual date, geography, transmission routes, iconography and archaeology are considered separately.

## Site structure

`index.html` is the public homepage. `episodes.js` contains the episode catalog, while `content/ko/` and `content/en/` hold the bilingual episode texts. `episode.html` renders individual installments. New installments can be appended without redesigning the homepage.

## Publishing future episodes

The intended publishing pipeline is: write/review an installment → add Korean and English content files → append metadata to `episodes.js` → commit to `main` → GitHub Pages rebuilds the public site. A workflow scaffold is included so future automated publishing can be connected to a trusted content-generation source without changing the site architecture.

> The repository is public. Reference links should point to reputable primary-text editions, museums, universities, archaeological institutions, or established scholarly resources whenever practical.
