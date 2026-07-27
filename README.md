# 🚀 8086 EMU Pro - Elite Intel 8086 CPU Simulator

<div align="center">

![App Header](https://img.shields.io/badge/Architecture-16--bit-red?style=for-the-badge&logo=cpu-z)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Assembler](https://img.shields.io/badge/8086-Assembly-green?style=for-the-badge&logo=intel)
![Ads](https://img.shields.io/badge/Ads-AdMob_Integrated-orange?style=for-the-badge&logo=google-ads)
![IAP](https://img.shields.io/badge/Monetization-In--App_Purchases-gold?style=for-the-badge&logo=google-play)

</div>

---

### 📖 Professional Overview | نظرة عامة احترافية

**English:**  
**8086 EMU Pro** is a pinnacle of computer architecture simulation, meticulously engineered for software enthusiasts and engineering students. It provides a high-fidelity, visually immersive environment to master the Intel 8086 microprocessor, featuring professional-grade debugging tools, real-time register monitoring, and a premium multi-lingual interface.

**العربية:**  
يُعد **8086 EMU Pro** قمة في هندسة محاكاة بنية الحاسوب، حيث تم تصميمه بدقة متناهية لعشاق البرمجيات وطلاب الهندسة. يوفر التطبيق بيئة غامرة بصرياً وعالية الدقة لإتقان معالج Intel 8086، مع أدوات تصحيح أخطاء احترافية، ومراقبة فورية للسجلات، وواجهة نخبوية تدعم لغات متعددة.

---

## 🌟 Advanced Simulation Features | ميزات المحاكاة المتقدمة

### 🖥️ Virtual Architecture | البنية الافتراضية
- **16-Bit Precision:** Full emulation of General Purpose (AX, BX, CX, DX), Index (SI, DI), and Pointer (BP, SP) registers.  
  **دقة 16 بت:** محاكاة كاملة للسجلات العامة (AX, BX, CX, DX)، وسجلات الفهرسة (SI, DI)، والمؤشرات (BP, SP).
- **Segmented Memory:** 1MB addressable memory space with CS, DS, SS, and ES management.  
  **الذاكرة المقسمة:** مساحة ذاكرة قابلة للعنونة تصل إلى 1 ميجابايت مع إدارة كاملة لسجلات المقاطع (CS, DS, SS, ES).
- **Flag Management:** Real-time monitoring of all system flags (Carry, Zero, Sign, Overflow, etc.).  
  **إدارة الأعلام:** مراقبة فورية لجميع أعلام النظام (Carry, Zero, Sign, Overflow، إلخ).
- **Stack Visualization:** Dedicated viewer for the system stack with real-time push/pop tracking.  
  **تصوير المكدس:** عرض مخصص لمكدس النظام مع تتبع عمليات الدفع (Push) والسحب (Pop) في الوقت الفعلي.
- **Memory Viewer:** Inspect and modify any memory cell with hex/ASCII views and address jumping.  
  **عرض الذاكرة:** فحص وتعديل أي خلية ذاكرة مع عرض بالصيغة الست عشرية (Hex) ورموز ASCII، مع ميزة القفز للعناوين.
- **Virtual Console:** Support for standard I/O interrupts for character and string output.  
  **الكونسول الافتراضي:** دعم مقاطعات الإدخال والإخراج القياسية لإخراج الحروف والنصوص.
- **Step-by-Step Debugging:** Execute instruction by instruction with full execution history.  
  **تصحيح الأخطاء خطوة بخطوة:** تنفيذ التعليمات واحدة تلو الأخرى مع سجل كامل لتاريخ التنفيذ.

---

## 💎 Pro & Free Versions | النسخة المجانية والمحترفة

### 🏆 Pro Version (Lifetime Unlock) | نسخة البرو (فتح مدى الحياة)
- **🚫 Ad-Free:** Complete removal of all Banner and Interstitial ads.  
  **خالٍ من الإعلانات:** إزالة كاملة لجميع الإعلانات المنبثقة والشريطية.
- **🔓 Algorithm Library:** Access to advanced samples (Sorting, Searching, Matrix Ops).  
  **مكتبة الخوارزميات:** الوصول إلى أمثلة متقدمة (الفرز، البحث، عمليات المصفوفات).
- **🎨 Premium Themes:** Exclusive high-fidelity developer themes.  
  **سمات مميزة:** قوالب حصرية عالية الدقة مصممة للمطورين.
- **⚡ Pro Priority:** Optimized performance and premium app identity.  
  **أولوية البرو:** أداء محسن وهوية تطبيق متميزة.

---

## 🛠️ Instruction Set Support | دعم مجموعة التعليمات

| Category | Instructions |
| :--- | :--- |
| **Data Transfer** | `MOV`, `PUSH`, `POP`, `XCHG`, `LEA`, `LDS`, `LES`, `XLAT`, `LAHF`, `SAHF`, `PUSHF`, `POPF`, `IN`, `OUT` |
| **Arithmetic** | `ADD`, `ADC`, `SUB`, `SBB`, `MUL`, `IMUL`, `DIV`, `IDIV`, `INC`, `DEC`, `NEG`, `CMP`, `CBW`, `CWD`, `AAA`, `AAS`, `AAM`, `AAD`, `DAA`, `DAS` |
| **Logical** | `AND`, `OR`, `XOR`, `NOT`, `TEST` |
| **Shift/Rotate**| `SHL`/`SAL`, `SHR`, `SAR`, `ROL`, `ROR`, `RCL`, `RCR` |
| **String Ops** | `MOVS`, `CMPS`, `SCAS`, `LODS`, `STOS`, `REP`/`REPE`/`REPZ`/`REPNE`/`REPNZ` |
| **Processor** | `STC`, `CLC`, `CMC`, `STD`, `CLD`, `STI`, `CLI`, `HLT`, `NOP`, `WAIT`, `ESC`, `LOCK` |
| **Flow Control**| `JMP`, `CALL`, `RET`, `JZ`/`JE`, `JNZ`/`JNE`, `JA`/`JAE`, `JB`/`JBE`, `JG`/`JGE`, `JL`/`JLE`, `LOOP`, `LOOPE`, `LOOPNE`, `JCXZ`, `INT`, `INTO`, `IRET` |
| **Directives** | `DB`, `DW`, Labels, Strings |

---

## 👨‍💻 Developed By | المطور

**Mohamad Mujahed Jesri | محمد مجاهد جسري**  
*Software Engineer & Systems Architect*
- 📧 [saefomomo@gmail.com](mailto:saefomomo@gmail.com)
- 🌐 [Portfolio](https://mohamad-mujahed-jesri.netlify.app/)
- 💬 [WhatsApp](https://wa.me/963967126407)

---

<div align="center">
  <i>Engineered with precision for the global assembly community. | صُمم بدقة لمجتمع مبرمجي الأسمبلي حول العالم.</i>
</div>
