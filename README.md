<div align="center">

# Sıfırdan DeepSeek — Verimli LLM Mimarisi
### Sezgiden Kodlamaya

[![YouTube](https://img.shields.io/badge/YouTube-Dersleri%20izle-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/playlist?list=PLWopEpVvYXko)
[![Lisans](https://img.shields.io/badge/Lisans-Apache%202.0-4c1?style=for-the-badge)](LICENSE)

</div>

> **🇬🇧 In English** — A Turkish-language course that builds DeepSeek's efficient LLM architecture
> from scratch in PyTorch, starting from GPT-2 and evolving it step by step into a DeepSeek-style
> model. Every concept is first built as intuition on a diagram, then written line by line in code.
> Everything runs in a single notebook on a free Kaggle GPU.

Bu seri, bir önceki serimiz olan **Sıfırdan ChatGPT ve LLM**'nin devamıdır. Orada GPT-2'yi
sıfırdan inşa etmiştik; bu seride ise GPT-2'yi çıkış noktası alarak DeepSeek'in verimli
mimarisine adım adım evrilteceğiz.

Her ders bir öncekinin açtığı sorunla başlar. Kavramları formüllere boğulmadan, şemalar ve
sade bir mantıkla ele alıyoruz. Sonra kodu adım adım kendimiz yazıyoruz.

**Sezgiden kodlamaya: verimli LLM mimarisi yazma sürecine hoş geldin.**

---

## Nasıl çalıştırılır

Depoda tek bir defter var: **`FULL-SERIES.ipynb`**. Serinin bütün kodu içinde.

| Ortam | Ne yapmalısın |
| --- | --- |
| **Kaggle** ⭐ | Defteri yükle, hızlandırıcıyı GPU yap, *Run All*. Serinin sınandığı ortam bu. |
| **Colab** | Defteri aç, çalışma zamanını GPU yap, *Tümünü çalıştır*. |
| **Yerel** | Depoyu klonla, defteri kök dizinde aç. Veri yanında olduğu için indirme bile olmaz. |

Defter veriyi üç yerde arar: yanındaki `_data/` klasörü, Kaggle girdileri, son çare olarak
bu depo. Yani yalnız `.ipynb` dosyasını alıp Kaggle'a atsan da eksiksiz çalışır.

## Depoda ne var

| Yol | Ne |
| --- | --- |
| `FULL-SERIES.ipynb` | serinin bütün kodu, tek defter |
| `_data/how-words-work.txt` | ön eğitim korpusu |
| `part-1-bridge/` | ders 1'in anlatım haritası |

Anlatım haritaları **Excalidraw** dosyasıdır: sürükleyip bırakınca açılır, üstüne yazabilir,
kendi notlarını ekleyebilirsin. Her bölümün haritası, o bölümün videosu yayımlandıkça
buraya eklenir.

## Müfredat

**Bölüm 1 · Köprü**

1. GPT'den DeepSeek'e: Köprü

**Bölüm 2 · Attention Gelişimi**

2. KV Cache: Tekrar Hesaplamaktan Kurtulmak
3. MQA / GQA: Başlık Sayısını Azaltmak
4. MLA: Multi-Head Latent Attention

**Bölüm 3 · RoPE**

5. RoPE: Döndürerek Konum Kodlamak
6. MLA + RoPE: İkisini Birleştirmek

**Bölüm 4 · Mixture of Experts**

7. MoE: Uzmanların Karışımı
8. Load Balancing: Yükü Dengelemek
9. DeepSeekMoE: DeepSeek'in MoE Tasarımı

**Bölüm 5 · Eğitim Verimliliği**

10. MTP: Birden Fazla Token Tahmini
11. FP8: Quantization ile Verimlilik
12. mini-DeepSeek: Her Şeyi Birleştir

---

## Lisans

Bu depo [Apache 2.0](LICENSE) ile lisanslanmıştır.
Türkçe anlatım, şemalar ve veri bu seriye özgüdür.

