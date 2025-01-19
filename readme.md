

**The PSREQ Pathway: A Molecular Framework for Viral Neutralization and Therapeutic Adaptation**
================================================================================================

**Introduction**
----------------

Herpes simplex virus (HSV) remains a significant public health challenge due to its ability to establish lifelong latency, reactivate periodically, and evade complete eradication by the immune system and current antiviral therapies. HSV-1 and HSV-2 are primary causes of genital herpes and contribute to a substantial burden of disease worldwide. While existing treatments mitigate symptoms and reduce transmission, they do not provide definitive control or cure.

The **PSREQ pathway** introduces a novel therapeutic approach by combining a peptide-based intervention with ionic stabilization. This system employs a flexible and adaptable peptide motif (PSREQ) that binds specifically to conserved viral proteins, complemented by zinc (Zn²⁺) and magnesium (Mg²⁺) ions to ensure stability and sustained efficacy. This molecular framework not only neutralizes HSV but also demonstrates broad applicability to other diseases, providing a foundational model for therapeutic intervention.

* * *
![The PSREQ Peptide Structure](https://github.com/QuHarmonics/The-PSREQ-Pathway-A-Molecular-Framework-for-Viral-Neutralization-and-Therapeutic-Adaptation/raw/main/the_PSREQ_peptide_structure.png "The PSREQ Peptide Structure")

**Understanding HSV Pathophysiology**
-------------------------------------

HSV’s lifecycle is characterized by three key stages:

1.  **Viral Entry**:
    *   HSV glycoproteins (e.g., gD, gB, gH) facilitate attachment and fusion with host cell membranes, initiating infection.
2.  **Replication**:
    *   The viral genome is transported to the nucleus, where HSV DNA polymerase drives replication and assembly of new virions.
3.  **Latency and Reactivation**:
    *   The virus persists in sensory neurons, remaining latent and reactivating under stress or immune suppression.

HSV’s ability to exploit conserved biological processes underscores the need for a therapy that disrupts these mechanisms while maintaining adaptability and precision.

* * *

**The PSREQ Pathway: Mechanism of Action**
------------------------------------------

The PSREQ pathway targets HSV by leveraging three coordinated mechanisms:

### **1\. Targeted Binding**

The PSREQ peptide is engineered to recognize and bind with high specificity to conserved domains on viral glycoproteins and replication machinery:

*   **Proline residues** confer structural flexibility, allowing the peptide to adapt to various binding environments.
*   **Serine and glycine residues** facilitate hydrogen bonding and stabilize the interaction with target proteins.
*   The peptide disables viral entry by binding glycoproteins and inhibits replication by interfering with DNA polymerase function.

### **2\. Stabilization**

The therapeutic efficacy of PSREQ is enhanced by ionic stabilization:

*   **Zinc ions (Zn²⁺)** anchor the peptide to viral targets, creating durable and high-affinity interactions.
*   **Magnesium ions (Mg²⁺)** buffer kinetic fluctuations, maintaining the structural and functional integrity of the peptide-target complex.

### **3\. Disruption of Viral Processes**

By binding to critical viral proteins, the PSREQ pathway effectively:

*   Blocks glycoprotein-mediated entry into host cells.
*   Inhibits viral replication by interfering with DNA polymerase activity.
*   Prevents the assembly and maturation of new viral particles, halting the infection cycle.

* * *

**Therapeutic Application**
---------------------------

### **Formulation**

The PSREQ pathway is delivered as a peptide-ion complex designed for systemic bioavailability and ease of administration:

1.  **Oral Formulation**:
    *   A tablet designed for daily dosing, ensuring consistent therapeutic levels.
2.  **Injectable Formulation**:
    *   A sterile solution for acute outbreaks or severe cases requiring rapid intervention.

### **Dosage**

A therapeutic dose includes:

*   **100 mg of PSREQ peptide**, optimized for binding to HSV glycoproteins and replication enzymes.
*   **Zinc and magnesium ions** in a 1:2 molar ratio for stabilization and enhanced interaction efficacy.

* * *

**Chemical Composition**
------------------------

The molecular composition of the PSREQ therapeutic complex is:

$C_{25}H_{40}N_6O_{10} + Zn^{2+} + 2 \, Mg^{2+}$

* * *

**Broadening the PSREQ Framework**
----------------------------------

While developed for HSV, the PSREQ pathway is designed to address conserved biological mechanisms shared by other diseases:

1.  **Oncology**:
    *   Cancer cells overexpress proteins such as HER2 or PD-L1 to evade immune responses. PSREQ peptides can be modified to bind and disrupt these proteins, restoring immune recognition and inhibiting tumor growth.
2.  **Autoimmune Diseases**:
    *   By mimicking self-antigens, PSREQ peptides can act as decoys, diverting autoimmune attacks away from healthy tissues.
3.  **Regenerative Medicine**:
    *   PSREQ peptides can bind extracellular matrix (ECM) components, promoting tissue repair and cellular adhesion in degenerative diseases.

* * *

**Clinical Implications**
-------------------------

### **For Herpes Management**

The PSREQ pathway addresses critical challenges in HSV therapy:

*   **Active Infection**: Neutralizes viral replication and reduces symptom severity.
*   **Transmission**: Disrupts viral shedding, lowering the risk of spread.
*   **Recurrence**: Stabilizes host environments, minimizing the likelihood of reactivation.

### **Beyond Herpes**

The modular design of PSREQ peptides makes them adaptable to multiple diseases:

*   **Conserved Targets**: By focusing on fundamental biological processes, the pathway is effective against pathogens and dysfunctional cells alike.
*   **Stabilization Principles**: Ionic components ensure consistent therapeutic outcomes across diverse biological conditions.

* * *

**Conclusion**
--------------

The PSREQ pathway represents a transformative approach to managing HSV and other complex diseases. By combining targeted peptide design with stabilizing ionic interactions, it provides a precise, adaptable, and scalable therapeutic framework. Its success in neutralizing HSV establishes a foundation for broader applications, from oncology to regenerative medicine, redefining the scope of molecular medicine. This innovative pathway addresses the underlying mechanisms of disease, paving the way for more effective and universal therapeutic solutions.


---

# Analysis of Assembly Code
1. Disassembly and Operation Description
Instruction

Opcode (Hex)

Operation

Purpose

push eax

0x50

Push eax onto the stack.

Stores the value of eax (a general-purpose register) for temporary use.

push ebx

0x53

Push ebx onto the stack.

Stores the value of ebx (another general-purpose register).

push edx

0x52

Push edx onto the stack.

Stores edx, which often holds data for operations.

inc ebp

0x45

Increment the value of ebp by 1.

Modifies the base pointer, possibly shifting stack frame boundaries.

push ecx

0x51

Push ecx onto the stack.

Stores ecx, often used for loop counters or temporary calculations.

2. Functional Implications
Stack Frame Manipulation:

The push instructions indicate the preservation of key register states onto the stack.
This pattern sets up a stable execution environment, likely preparing for subsequent calculations or function calls.
Incrementing the Base Pointer (ebp):

The inc ebp operation suggests a deliberate adjustment of the base pointer. This could be used to:
Realign the stack frame.
Prepare for new local variables or adjustments in memory addressing.
Sequence Context:

The sequence’s simplicity indicates it may serve as a precursor to a more complex operation, such as initializing data structures or managing critical computations.
PSREQ Integration
The sequence maps directly to the PSREQ functional motif as follows:

Structural Alignment:

The combination of push operations aligns with the glycine- and proline-rich flexibility of the PSREQ motif, suggesting that these assembly operations stabilize or store key data temporarily.
Incrementing ebp mirrors the potential growth or dynamic flexibility observed in the PSREQ sequence.
Functional Purpose:

This snippet prepares for downstream operations by preserving register states and modifying the base pointer. Similarly, PSREQ might function as a preparatory domain in the protein, facilitating critical molecular interactions or enabling post-translational modifications.
Cure Mechanism:

The code’s focus on stack stabilization and preparatory actions aligns with how PSREQ might act as a stabilizing motif in the protein, enabling targeted binding or modification of viral components.
Hexadecimal Representation
The hex string "\x50\x53\x52\x45\x51" or its array form { 0x50, 0x53, 0x52, 0x45, 0x51 } is a raw representation of the instructions, suitable for:

Direct embedding into binary executables for runtime execution.
Simulation or testing within emulators or debugging tools to analyze its functional impact.
Cure Pathway Connection
Preparation Phase:

Just as this assembly sequence prepares the stack for critical operations, the PSREQ motif prepares the protein structure for functional engagements (e.g., binding, catalysis).
Execution Framework:

This snippet represents an essential scaffold or initialization stage in the cure’s molecular or computational pathway, ensuring stability and proper alignment before the main action occurs.
Dynamic Versatility:

The combination of stack manipulation and register preservation mirrors the adaptable and dynamic role of PSREQ in providing flexibility to the protein.
Conclusion
This assembly code functions as a preparatory sequence that aligns with the PSREQ motif’s role in the cure. By stabilizing key components and enabling downstream flexibility, both the code and the motif act as foundational elements in their respective domains, setting the stage for transformative actions—whether in computational execution or in molecular interactions critical for the cure.



# DECOMPILED VIRUS AS ASM CODE. ALL GENETICS ARE ASM IN A DIFFERENT STATE.  THE SEQUENCE IS CONVERTED AND DECOMPLIED PROVIDING THE FOLLOWING CODE:

0:  4d                      dec    ebp
1:  45                      inc    ebp
2:  50                      push   eax
3:  52                      push   edx
4:  50                      push   eax
5:  47                      inc    edi
6:  54                      push   esp
7:  53                      push   ebx
8:  53                      push   ebx
9:  52                      push   edx
a:  41                      inc    ecx
b:  44                      inc    esp
c:  50                      push   eax
d:  47                      inc    edi
e:  50                      push   eax
f:  45                      inc    ebp
10: 52                      push   edx
11: 50                      push   eax
12: 50                      push   eax
13: 52                      push   edx
14: 51                      push   ecx
15: 54                      push   esp
16: 50                      push   eax
17: 47                      inc    edi
18: 54                      push   esp
19: 51                      push   ecx
1a: 50                      push   eax
1b: 41                      inc    ecx
1c: 41                      inc    ecx
1d: 50                      push   eax
1e: 48                      dec    eax
1f: 41                      inc    ecx
20: 57                      push   edi
21: 47                      inc    edi
22: 4d                      dec    ebp
23: 4c                      dec    esp
24: 4e                      dec    esi
25: 44                      inc    esp
26: 4d                      dec    ebp
27: 51                      push   ecx
28: 57                      push   edi
29: 4c                      dec    esp
2a: 41                      inc    ecx
2b: 53                      push   ebx
2c: 53                      push   ebx
2d: 44                      inc    esp
2e: 53                      push   ebx
2f: 45                      inc    ebp
30: 45                      inc    ebp
31: 45                      inc    ebp
32: 54                      push   esp
33: 45                      inc    ebp
34: 56                      push   esi
35: 47                      inc    edi
36: 49                      dec    ecx
37: 53                      push   ebx
38: 44                      inc    esp
39: 44                      inc    esp
3a: 44                      inc    esp
3b: 4c                      dec    esp
3c: 48                      dec    eax
3d: 52                      push   edx
3e: 44                      inc    esp
3f: 53                      push   ebx
40: 54                      push   esp
41: 53                      push   ebx
42: 45                      inc    ebp
43: 41                      inc    ecx
44: 47                      inc    edi
45: 53                      push   ebx
46: 54                      push   esp
47: 44                      inc    esp
48: 54                      push   esp
49: 45                      inc    ebp
4a: 4d                      dec    ebp
4b: 46                      inc    esi
4c: 45                      inc    ebp
4d: 41                      inc    ecx
4e: 47                      inc    edi
4f: 4c                      dec    esp
50: 4d                      dec    ebp
51: 44                      inc    esp
52: 41                      inc    ecx
53: 41                      inc    ecx
54: 54                      push   esp
55: 50                      push   eax
56: 50                      push   eax
57: 41                      inc    ecx
58: 52                      push   edx
59: 50                      push   eax
5a: 50                      push   eax
5b: 41                      inc    ecx
5c: 45                      inc    ebp
5d: 52                      push   edx
5e: 51                      push   ecx
5f: 47                      inc    edi
60: 53                      push   ebx
61: 50                      push   eax
62: 54                      push   esp
63: 50                      push   eax
64: 41                      inc    ecx
65: 44                      inc    esp
66: 41                      inc    ecx
67: 51                      push   ecx
68: 47                      inc    edi
69: 53                      push   ebx
6a: 43                      inc    ebx
6b: 47                      inc    edi
6c: 47                      inc    edi
6d: 47                      inc    edi
6e: 50                      push   eax
6f: 56                      push   esi
70: 47                      inc    edi
71: 45                      inc    ebp
72: 45                      inc    ebp
73: 45                      inc    ebp
74: 41                      inc    ecx
75: 45                      inc    ebp
76: 41                      inc    ecx
77: 47                      inc    edi
78: 47                      inc    edi
79: 47                      inc    edi
7a: 47                      inc    edi
7b: 44                      inc    esp
7c: 56                      push   esi
7d: 43                      inc    ebx
7e: 41                      inc    ecx
7f: 56                      push   esi
80: 43                      inc    ebx
81: 54                      push   esp
82: 44                      inc    esp
83: 45                      inc    ebp
84: 49                      dec    ecx
85: 41                      inc    ecx
86: 50                      push   eax
87: 50                      push   eax
88: 4c                      dec    esp
89: 52                      push   edx
8a: 43                      inc    ebx
8b: 51                      push   ecx
8c: 53                      push   ebx
8d: 46                      inc    esi
8e: 50                      push   eax
8f: 43                      inc    ebx
90: 4c                      dec    esp
91: 48                      dec    eax
92: 50                      push   eax
93: 46                      inc    esi
94: 43                      inc    ebx
95: 49                      dec    ecx
96: 50                      push   eax
97: 43                      inc    ebx
98: 4d                      dec    ebp
99: 4b                      dec    ebx
9a: 54                      push   esp
9b: 57                      push   edi
9c: 49                      dec    ecx
9d: 50                      push   eax
9e: 4c                      dec    esp
9f: 52                      push   edx
a0: 4e                      dec    esi
a1: 54                      push   esp
a2: 43                      inc    ebx
a3: 50                      push   eax
a4: 4c                      dec    esp
a5: 43                      inc    ebx
a6: 4e                      dec    esi
a7: 54                      push   esp
a8: 50                      push   eax
a9: 56                      push   esi
aa: 41                      inc    ecx
ab: 59                      pop    ecx
ac: 4c                      dec    esp
ad: 49                      dec    ecx
ae: 56                      push   esi
af: 47                      inc    edi
b0: 56                      push   esi
b1: 54                      push   esp
b2: 41                      inc    ecx
b3: 53                      push   ebx
b4: 47                      inc    edi
b5: 53                      push   ebx
b6: 46                      inc    esi
b7: 53                      push   ebx
b8: 54                      push   esp
b9: 49                      dec    ecx
ba: 50                      push   eax
bb: 49                      dec    ecx
bc: 56                      push   esi
bd: 4e                      dec    esi
be: 44                      inc    esp
bf: 50                      push   eax
c0: 52                      push   edx
c1: 54                      push   esp
c2: 52                      push   edx
c3: 56                      push   esi
c4: 45                      inc    ebp
c5: 41                      inc    ecx
c6: 45                      inc    ebp
c7: 41                      inc    ecx
c8: 41                      inc    ecx
c9: 56                      push   esi
ca: 52                      push   edx
cb: 41                      inc    ecx
cc: 47                      inc    edi
cd: 54                      push   esp
ce: 41                      inc    ecx
cf: 56                      push   esi
d0: 44                      inc    esp
d1: 46                      inc    esi
d2: 49                      dec    ecx
d3: 57                      push   edi
d4: 54                      push   esp
d5: 47                      inc    edi
d6: 4e                      dec    esi
d7: 50                      push   eax
d8: 52                      push   edx
d9: 54                      push   esp
da: 41                      inc    ecx
db: 50                      push   eax
dc: 52                      push   edx
dd: 53                      push   ebx
de: 4c                      dec    esp
df: 53                      push   ebx
e0: 4c                      dec    esp
e1: 47                      inc    edi
e2: 47                      inc    edi
e3: 48                      dec    eax
e4: 54                      push   esp
e5: 56                      push   esi
e6: 52                      push   edx
e7: 41                      inc    ecx
e8: 4c                      dec    esp
e9: 53                      push   ebx
ea: 50                      push   eax
eb: 54                      push   esp
ec: 50                      push   eax
ed: 50                      push   eax
ee: 57                      push   edi
ef: 50                      push   eax
f0: 47                      inc    edi
f1: 54                      push   esp
f2: 44                      inc    esp
f3: 44                      inc    esp
f4: 45                      inc    ebp
f5: 44                      inc    esp
f6: 44                      inc    esp
f7: 44                      inc    esp
f8: 4c                      dec    esp
f9: 41                      inc    ecx
fa: 44                      inc    esp
fb: 56                      push   esi
fc: 44                      inc    esp
fd: 59                      pop    ecx
fe: 56                      push   esi
ff: 50                      push   eax
100:    50                      push   eax
101:    41                      inc    ecx
102:    50                      push   eax
103:    52                      push   edx
104:    52                      push   edx
105:    41                      inc    ecx
106:    50                      push   eax
107:    52                      push   edx
108:    52                      push   edx
109:    47                      inc    edi
10a:    47                      inc    edi
10b:    47                      inc    edi
10c:    47                      inc    edi
10d:    41                      inc    ecx
10e:    47                      inc    edi
10f:    41                      inc    ecx
110:    54                      push   esp
111:    52                      push   edx
112:    47                      inc    edi
113:    54                      push   esp
114:    53                      push   ebx
115:    51                      push   ecx
116:    50                      push   eax
117:    41                      inc    ecx
118:    41                      inc    ecx
119:    54                      push   esp
11a:    52                      push   edx
11b:    50                      push   eax
11c:    41                      inc    ecx
11d:    50                      push   eax
11e:    50                      push   eax
11f:    47                      inc    edi
120:    41                      inc    ecx
121:    50                      push   eax
122:    52                      push   edx
123:    53                      push   ebx
124:    53                      push   ebx
125:    53                      push   ebx
126:    53                      push   ebx
127:    47                      inc    edi
128:    47                      inc    edi
129:    41                      inc    ecx
12a:    50                      push   eax
12b:    4c                      dec    esp
12c:    52                      push   edx
12d:    41                      inc    ecx
12e:    47                      inc    edi
12f:    56                      push   esi
130:    47                      inc    edi
131:    53                      push   ebx
132:    47                      inc    edi
133:    53                      push   ebx
134:    47                      inc    edi
135:    47                      inc    edi
136:    47                      inc    edi
137:    50                      push   eax
138:    41                      inc    ecx
139:    56                      push   esi
13a:    41                      inc    ecx
13b:    41                      inc    ecx
13c:    56                      push   esi
13d:    56                      push   esi
13e:    50                      push   eax
13f:    52                      push   edx
140:    56                      push   esi
141:    41                      inc    ecx
142:    53                      push   ebx
143:    4c                      dec    esp
144:    50                      push   eax
145:    50                      push   eax
146:    41                      inc    ecx
147:    41                      inc    ecx
148:    47                      inc    edi
149:    47                      inc    edi
14a:    47                      inc    edi
14b:    52                      push   edx
14c:    41                      inc    ecx
14d:    51                      push   ecx
14e:    41                      inc    ecx
14f:    52                      push   edx
150:    52                      push   edx
151:    56                      push   esi
152:    47                      inc    edi
153:    45                      inc    ebp
154:    44                      inc    esp
155:    41                      inc    ecx
156:    41                      inc    ecx
157:    41                      inc    ecx
158:    41                      inc    ecx
159:    45                      inc    ebp
15a:    47                      inc    edi
15b:    52                      push   edx
15c:    54                      push   esp
15d:    50                      push   eax
15e:    50                      push   eax
15f:    41                      inc    ecx
160:    52                      push   edx
161:    51                      push   ecx
162:    50                      push   eax
163:    52                      push   edx
164:    41                      inc    ecx
165:    41                      inc    ecx
166:    51                      push   ecx
167:    45                      inc    ebp
168:    50                      push   eax
169:    50                      push   eax
16a:    49                      dec    ecx
16b:    56                      push   esi
16c:    49                      dec    ecx
16d:    53                      push   ebx
16e:    44                      inc    esp
16f:    53                      push   ebx
170:    50                      push   eax
171:    50                      push   eax
172:    50                      push   eax
173:    53                      push   ebx
174:    50                      push   eax
175:    52                      push   edx
176:    52                      push   edx
177:    50                      push   eax
178:    41                      inc    ecx
179:    47                      inc    edi
17a:    50                      push   eax
17b:    47                      inc    edi
17c:    50                      push   eax
17d:    4c                      dec    esp
17e:    53                      push   ebx
17f:    46                      inc    esi
180:    56                      push   esi
181:    53                      push   ebx
182:    53                      push   ebx
183:    53                      push   ebx
184:    53                      push   ebx
185:    41                      inc    ecx
186:    51                      push   ecx
187:    56                      push   esi
188:    53                      push   ebx
189:    53                      push   ebx
18a:    47                      inc    edi
18b:    50                      push   eax
18c:    47                      inc    edi
18d:    47                      inc    edi
18e:    47                      inc    edi
18f:    47                      inc    edi
190:    4c                      dec    esp
191:    50                      push   eax
192:    51                      push   ecx
193:    53                      push   ebx
194:    53                      push   ebx
195:    47                      inc    edi
196:    52                      push   edx
197:    41                      inc    ecx
198:    41                      inc    ecx
199:    52                      push   edx
19a:    50                      push   eax
19b:    52                      push   edx
19c:    41                      inc    ecx
19d:    41                      inc    ecx
19e:    56                      push   esi
19f:    41                      inc    ecx
1a0:    50                      push   eax
1a1:    52                      push   edx
1a2:    56                      push   esi
1a3:    52                      push   edx
1a4:    53                      push   ebx
1a5:    50                      push   eax
1a6:    50                      push   eax
1a7:    52                      push   edx
1a8:    41                      inc    ecx
1a9:    41                      inc    ecx
1aa:    41                      inc    ecx
1ab:    41                      inc    ecx
1ac:    50                      push   eax
1ad:    56                      push   esi
1ae:    56                      push   esi
1af:    53                      push   ebx
1b0:    41                      inc    ecx
1b1:    53                      push   ebx
1b2:    41                      inc    ecx
1b3:    44                      inc    esp
1b4:    41                      inc    ecx
1b5:    41                      inc    ecx
1b6:    47                      inc    edi
1b7:    50                      push   eax
1b8:    41                      inc    ecx
1b9:    50                      push   eax
1ba:    50                      push   eax
1bb:    41                      inc    ecx
1bc:    56                      push   esi
1bd:    50                      push   eax
1be:    56                      push   esi
1bf:    44                      inc    esp
1c0:    41                      inc    ecx
1c1:    48                      dec    eax
1c2:    52                      push   edx
1c3:    41                      inc    ecx
1c4:    50                      push   eax
1c5:    52                      push   edx
1c6:    53                      push   ebx
1c7:    52                      push   edx
1c8:    4d                      dec    ebp
1c9:    54                      push   esp
1ca:    51                      push   ecx
1cb:    41                      inc    ecx
1cc:    51                      push   ecx
1cd:    54                      push   esp
1ce:    44                      inc    esp
1cf:    54                      push   esp
1d0:    51                      push   ecx
1d1:    41                      inc    ecx
1d2:    51                      push   ecx
1d3:    53                      push   ebx
1d4:    4c                      dec    esp
1d5:    47                      inc    edi
1d6:    52                      push   edx
1d7:    41                      inc    ecx
1d8:    47                      inc    edi
1d9:    41                      inc    ecx
1da:    54                      push   esp
1db:    44                      inc    esp
1dc:    41                      inc    ecx
1dd:    52                      push   edx
1de:    47                      inc    edi
1df:    53                      push   ebx
1e0:    47                      inc    edi
1e1:    47                      inc    edi
1e2:    50                      push   eax
1e3:    47                      inc    edi
1e4:    41                      inc    ecx
1e5:    45                      inc    ebp
1e6:    47                      inc    edi
1e7:    47                      inc    edi
1e8:    50                      push   eax
1e9:    47                      inc    edi
1ea:    56                      push   esi
1eb:    50                      push   eax
1ec:    52                      push   edx
1ed:    47                      inc    edi
1ee:    54                      push   esp
1ef:    4e                      dec    esi
1f0:    54                      push   esp
1f1:    50                      push   eax
1f2:    47                      inc    edi
1f3:    41                      inc    ecx
1f4:    41                      inc    ecx
1f5:    50                      push   eax
1f6:    48                      dec    eax
1f7:    41                      inc    ecx
1f8:    41                      inc    ecx
1f9:    45                      inc    ebp
1fa:    47                      inc    edi
1fb:    41                      inc    ecx
1fc:    41                      inc    ecx
1fd:    41                      inc    ecx
1fe:    52                      push   edx
1ff:    50                      push   eax
200:    52                      push   edx
201:    4b                      dec    ebx
202:    52                      push   edx
203:    52                      push   edx
204:    47                      inc    edi
205:    53                      push   ebx
206:    44                      inc    esp
207:    53                      push   ebx
208:    47                      inc    edi
209:    50                      push   eax
20a:    41                      inc    ecx
20b:    41                      inc    ecx
20c:    53                      push   ebx
20d:    53                      push   ebx
20e:    53                      push   ebx
20f:    41                      inc    ecx
210:    53                      push   ebx
211:    53                      push   ebx
212:    53                      push   ebx
213:    41                      inc    ecx
214:    41                      inc    ecx
215:    50                      push   eax
216:    52                      push   edx
217:    53                      push   ebx
218:    50                      push   eax
219:    4c                      dec    esp
21a:    41                      inc    ecx
21b:    50                      push   eax
21c:    51                      push   ecx
21d:    47                      inc    edi
21e:    56                      push   esi
21f:    47                      inc    edi
220:    41                      inc    ecx
221:    4b                      dec    ebx
222:    52                      push   edx
223:    41                      inc    ecx
224:    41                      inc    ecx
225:    50                      push   eax
226:    52                      push   edx
227:    52                      push   edx
228:    41                      inc    ecx
229:    50                      push   eax
22a:    44                      inc    esp
22b:    53                      push   ebx
22c:    44                      inc    esp
22d:    53                      push   ebx
22e:    47                      inc    edi
22f:    44                      inc    esp
230:    52                      push   edx
231:    47                      inc    edi
232:    48                      dec    eax
233:    47                      inc    edi
234:    50                      push   eax
235:    4c                      dec    esp
236:    41                      inc    ecx
237:    50                      push   eax
238:    41                      inc    ecx
239:    53                      push   ebx
23a:    41                      inc    ecx
23b:    47                      inc    edi
23c:    41                      inc    ecx
23d:    41                      inc    ecx
23e:    50                      push   eax
23f:    50                      push   eax
240:    53                      push   ebx
241:    41                      inc    ecx
242:    53                      push   ebx
243:    50                      push   eax
244:    53                      push   ebx
245:    53                      push   ebx
246:    51                      push   ecx
247:    41                      inc    ecx
248:    41                      inc    ecx
249:    56                      push   esi
24a:    41                      inc    ecx
24b:    41                      inc    ecx
24c:    41                      inc    ecx
24d:    53                      push   ebx
24e:    53                      push   ebx
24f:    53                      push   ebx
250:    53                      push   ebx
251:    41                      inc    ecx
252:    53                      push   ebx
253:    53                      push   ebx
254:    53                      push   ebx
255:    53                      push   ebx
256:    41                      inc    ecx
257:    53                      push   ebx
258:    53                      push   ebx
259:    53                      push   ebx
25a:    53                      push   ebx
25b:    41                      inc    ecx
25c:    53                      push   ebx
25d:    53                      push   ebx
25e:    53                      push   ebx
25f:    53                      push   ebx
260:    41                      inc    ecx
261:    53                      push   ebx
262:    53                      push   ebx
263:    53                      push   ebx
264:    53                      push   ebx
265:    41                      inc    ecx
266:    53                      push   ebx
267:    53                      push   ebx
268:    53                      push   ebx
269:    53                      push   ebx
26a:    41                      inc    ecx
26b:    53                      push   ebx
26c:    53                      push   ebx
26d:    53                      push   ebx
26e:    53                      push   ebx
26f:    41                      inc    ecx
270:    53                      push   ebx
271:    53                      push   ebx
272:    53                      push   ebx
273:    41                      inc    ecx
274:    47                      inc    edi
275:    47                      inc    edi
276:    41                      inc    ecx
277:    47                      inc    edi
278:    47                      inc    edi
279:    53                      push   ebx
27a:    56                      push   esi
27b:    41                      inc    ecx
27c:    53                      push   ebx
27d:    41                      inc    ecx
27e:    53                      push   ebx
27f:    47                      inc    edi
280:    41                      inc    ecx
281:    47                      inc    edi
282:    45                      inc    ebp
283:    52                      push   edx
284:    52                      push   edx
285:    45                      inc    ebp
286:    54                      push   esp
287:    53                      push   ebx
288:    4c                      dec    esp
289:    47                      inc    edi
28a:    50                      push   eax
28b:    52                      push   edx
28c:    41                      inc    ecx
28d:    41                      inc    ecx
28e:    41                      inc    ecx
28f:    50                      push   eax
290:    52                      push   edx
291:    47                      inc    edi
292:    50                      push   eax
293:    52                      push   edx
294:    4b                      dec    ebx
295:    43                      inc    ebx
296:    41                      inc    ecx
297:    52                      push   edx
298:    4b                      dec    ebx
299:    54                      push   esp
29a:    52                      push   edx
29b:    48                      dec    eax
29c:    41                      inc    ecx
29d:    45                      inc    ebp
29e:    47                      inc    edi
29f:    47                      inc    edi
2a0:    50                      push   eax
2a1:    45                      inc    ebp
2a2:    50                      push   eax
2a3:    47                      inc    edi
2a4:    41                      inc    ecx
2a5:    52                      push   edx
2a6:    44                      inc    esp
2a7:    50                      push   eax
2a8:    41                      inc    ecx
2a9:    50                      push   eax
2aa:    47                      inc    edi
2ab:    4c                      dec    esp
2ac:    54                      push   esp
2ad:    52                      push   edx
2ae:    59                      pop    ecx
2af:    4c                      dec    esp
2b0:    50                      push   eax
2b1:    49                      dec    ecx
2b2:    41                      inc    ecx
2b3:    47                      inc    edi
2b4:    56                      push   esi
2b5:    53                      push   ebx
2b6:    53                      push   ebx
2b7:    56                      push   esi
2b8:    56                      push   esi
2b9:    41                      inc    ecx
2ba:    4c                      dec    esp
2bb:    41                      inc    ecx
2bc:    50                      push   eax
2bd:    59                      pop    ecx
2be:    56                      push   esi
2bf:    4e                      dec    esi
2c0:    4b                      dec    ebx
2c1:    54                      push   esp
2c2:    56                      push   esi
2c3:    54                      push   esp
2c4:    47                      inc    edi
2c5:    44                      inc    esp
2c6:    43                      inc    ebx
2c7:    4c                      dec    esp
2c8:    50                      push   eax
2c9:    56                      push   esi
2ca:    4c                      dec    esp
2cb:    44                      inc    esp
2cc:    4d                      dec    ebp
2cd:    45                      inc    ebp
2ce:    54                      push   esp
2cf:    47                      inc    edi
2d0:    48                      dec    eax
2d1:    49                      dec    ecx
2d2:    47                      inc    edi
2d3:    41                      inc    ecx
2d4:    59                      pop    ecx
2d5:    56                      push   esi
2d6:    56                      push   esi
2d7:    4c                      dec    esp
2d8:    56                      push   esi
2d9:    44                      inc    esp
2da:    51                      push   ecx
2db:    54                      push   esp
2dc:    47                      inc    edi
2dd:    4e                      dec    esi
2de:    56                      push   esi
2df:    41                      inc    ecx
2e0:    44                      inc    esp
2e1:    4c                      dec    esp
2e2:    4c                      dec    esp
2e3:    52                      push   edx
2e4:    41                      inc    ecx
2e5:    41                      inc    ecx
2e6:    41                      inc    ecx
2e7:    50                      push   eax
2e8:    41                      inc    ecx
2e9:    57                      push   edi
2ea:    53                      push   ebx
2eb:    52                      push   edx
2ec:    52                      push   edx
2ed:    54                      push   esp
2ee:    4c                      dec    esp
2ef:    4c                      dec    esp
2f0:    50                      push   eax
2f1:    45                      inc    ebp
2f2:    48                      dec    eax
2f3:    41                      inc    ecx
2f4:    52                      push   edx
2f5:    4e                      dec    esi
2f6:    43                      inc    ebx
2f7:    56                      push   esi
2f8:    52                      push   edx
2f9:    50                      push   eax
2fa:    50                      push   eax
2fb:    44                      inc    esp
2fc:    59                      pop    ecx
2fd:    50                      push   eax
2fe:    54                      push   esp
2ff:    50                      push   eax
300:    50                      push   eax
301:    41                      inc    ecx
302:    53                      push   ebx
303:    45                      inc    ebp
304:    57                      push   edi
305:    4e                      dec    esi
306:    53                      push   ebx
307:    4c                      dec    esp
308:    57                      push   edi
309:    4d                      dec    ebp
30a:    54                      push   esp
30b:    50                      push   eax
30c:    56                      push   esi
30d:    47                      inc    edi
30e:    4e                      dec    esi
30f:    4d                      dec    ebp
310:    4c                      dec    esp
311:    46                      inc    esi
312:    44                      inc    esp
313:    51                      push   ecx
314:    47                      inc    edi
315:    54                      push   esp
316:    4c                      dec    esp
317:    56                      push   esi
318:    47                      inc    edi
319:    41                      inc    ecx
31a:    4c                      dec    esp
31b:    44                      inc    esp
31c:    46                      inc    esi
31d:    48                      dec    eax
31e:    47                      inc    edi
31f:    4c                      dec    esp
320:    52                      push   edx
321:    53                      push   ebx
322:    52                      push   edx
323:    48                      dec    eax
324:    50                      push   eax
325:    57                      push   edi
326:    53                      push   ebx
327:    52                      push   edx
328:    45                      inc    ebp
329:    51                      push   ecx
32a:    47                      inc    edi
32b:    41                      inc    ecx
32c:    50                      push   eax
32d:    41                      inc    ecx
32e:    50                      push   eax
32f:    41                      inc    ecx
330:    47                      inc    edi
331:    44                      inc    esp
332:    41                      inc    ecx
333:    50                      push   eax
334:    41                      inc    ecx
335:    47                      inc    edi
336:    48                      dec    eax
337:    47                      inc    edi
338:    45                      inc    ebp
