### Bradley Rogue · Hollywood Rogue Ventures

Former Nashville editor of *Cash Box Magazine*, investigative journalist on the Great Pyramid of Giza, and science-fiction author. Here I build **PSYFR**: browser instruments for predictive chronology, rendering Jason Breshears' Archaix thesis as working calendrics. I also took apart the Ophis desktop engine and rebuilt it for the web, with tests that check every rebuild against the original.

**[Project hub](https://bradleyhomelinuxnet-prog.github.io/)** · **[Portfolio](https://rogue-ventures-portfolio.com/)**

#### PSYFR

| Project | What it is | Live | Tests |
|---|---|---|---|
| [natori-on-psyfr](https://github.com/bradleyhomelinuxnet-prog/natori-on-psyfr) | The predictive chronology engine: Ophis grammar × Chronicon calendrics. Self-contained, works offline. | [open](https://bradleyhomelinuxnet-prog.github.io/natori-on-psyfr/) | [![tests](https://github.com/bradleyhomelinuxnet-prog/natori-on-psyfr/actions/workflows/test.yml/badge.svg)](https://github.com/bradleyhomelinuxnet-prog/natori-on-psyfr/actions/workflows/test.yml) |
| [NatorionCipherPredictiveEngine](https://github.com/bradleyhomelinuxnet-prog/NatorionCipherPredictiveEngine) | Ophis v12 reverse-engineered and rebuilt in the browser: Natorion Cipher, Ophis Web, and the original app running without Electron. | [open](https://bradleyhomelinuxnet-prog.github.io/NatorionCipherPredictiveEngine/) | [![tests](https://github.com/bradleyhomelinuxnet-prog/NatorionCipherPredictiveEngine/actions/workflows/tests.yml/badge.svg)](https://github.com/bradleyhomelinuxnet-prog/NatorionCipherPredictiveEngine/actions/workflows/tests.yml) |
| [phoenix-chronicles-tools](https://github.com/bradleyhomelinuxnet-prog/phoenix-chronicles-tools) | Companion instruments and field guides for *The Phoenix CODEX 138 Palindromic*, plus the film production kit. | [open](https://bradleyhomelinuxnet-prog.github.io/phoenix-chronicles-tools/) | |
| [OPHIS-Pattern-Recognition-Event-Prediction_files](https://github.com/bradleyhomelinuxnet-prog/OPHIS-Pattern-Recognition-Event-Prediction_files) | Single-file builds of the Ophis instrument and the Chronicon engine. | [open](https://bradleyhomelinuxnet-prog.github.io/OPHIS-Pattern-Recognition-Event-Prediction_files/) | |

#### Small, tested examples

| Project | What it is | Live | Tests |
|---|---|---|---|
| [luhn-algorithm](https://github.com/bradleyhomelinuxnet-prog/luhn-algorithm) | The mod 10 checksum behind card numbers, with a step-by-step checker. | [open](https://bradleyhomelinuxnet-prog.github.io/luhn-algorithm/) | [![tests](https://github.com/bradleyhomelinuxnet-prog/luhn-algorithm/actions/workflows/test.yml/badge.svg)](https://github.com/bradleyhomelinuxnet-prog/luhn-algorithm/actions/workflows/test.yml) |
| [fizzbuzz](https://github.com/bradleyhomelinuxnet-prog/fizzbuzz) | FizzBuzz with pluggable rules and an interactive grid. | [open](https://bradleyhomelinuxnet-prog.github.io/fizzbuzz/) | [![tests](https://github.com/bradleyhomelinuxnet-prog/fizzbuzz/actions/workflows/test.yml/badge.svg)](https://github.com/bradleyhomelinuxnet-prog/fizzbuzz/actions/workflows/test.yml) |

#### How I work

- **Plain HTML, CSS and JavaScript.** Most pages are a single file with no build step, and run offline.
- **Tested against the original.** Every rebuild runs side by side with the engine it replaces, and the results are compared row by row.
- **Private by design.** The tools compute in your browser, and the dates you enter stay there.
