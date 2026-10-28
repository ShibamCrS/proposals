# ANRF portal fields for the full proposal (copy-paste source)

File ANRF/ARG/2026/010258/ENS. Everything below mirrors the technical document
(full-proposal.tex); keep the two in sync if either changes.

## Keywords (3 to 6, max 30 characters each)

1. Low-latency cryptography
2. Symmetric-key cryptanalysis
3. Automated cryptanalysis
4. Fault injection attacks
5. Microarchitectural security
6. Block cipher design

## Response to Referee Comments on the Pre-Proposal (field 15, max 500 words; this is about 190)

The committee and both expert reviewers assessed the pre-proposal favourably
and raised no objections. The only point to work on was that the objectives be
clearly delineated so that the project moves at a steady pace. This has been
incorporated in full.

Section 2 states five objectives, each with a hypothesis and numbered,
measurable success metrics against named baseline ciphers. Section 4.5
organises the work into six work packages (Table 1) with a lead institute,
duration and deliverables for each, and a risk and mitigation list. Section 6
gives a 48-month Gantt chart with eight milestones tied to the deliverables of
Section 5, four of them within the first three years as checkpoints for the
phased release of support. Section 3.4 records the preliminary results on which
each work package starts, including the investigators' published cryptanalysis
of three of the four target ciphers and their hardware-validated fault attacks.

No objective of the pre-proposal has been dropped or changed. The GPU-oriented
cryptanalysis and the indigenous cipher design listed there appear under
Objectives 1 and 4 respectively. No suggestion has been left unincorporated, so
no rebuttal is required.

## Any other relevant information

- The budget has been revised from the working draft to respect the ARG
  ceilings: travel Rs 5 lakh and contingency Rs 5 lakh for the whole project.
- Equipment (non-recurring, year 1): IIT Hyderabad, NVIDIA RTX PRO 6000 Blackwell
  96 GB GPU for an existing departmental workstation, Rs 22,53,800 incl. GST,
  two laptops (HP 440 G11, Rs 1,10,008 each) and one Apple M-series Mac mini
  (Rs 1,20,000) as a pointer-authentication target for WP4, and one small
  Supermicro AS-3015A-I mini-tower server (AMD EPYC 4565P, 64 GB DDR5 ECC,
  1 TB NVMe; Rs 3,50,000, indicative incl. GST) as the SME/SEV-SNP
  memory-encryption test bed for WP4. IIT Bhilai: two
  laptops (Rs 1,10,008 each), one NewAE CW310 Bergen Board, Kintex-7 K410T (NAE-CW310-K410T-NORM)
  (Rs 8,50,000) and one near-field EM probe set with preamplifier (Rs 6,75,000),
  both indicative including GST.
- [Optional, if obtained] Letter of intent from <collaborator> (<institution>)
  as Honorary Investigator is attached.
- Administrative nodal contact at the host institute: <name, designation,
  email, phone> (IIT Hyderabad R&D office).

## Budget: head-wise justification strings for the portal cells

Research Personnel (each institute): one JRF (SRF from year 3) and one
Research Associate-I for 48 months at ANRF rates plus HRA. IITH: PhD on
automated and ML-assisted cryptanalysis; RA on constraint-model library and
GPU attack implementations. IIT Bhilai: PhD on fault analysis of unrolled
implementations; RA on hardware targets, fault campaigns and DARC benchmarking.

Consumables, IITH: solver licences (Gurobi/CPLEX academic), cloud-GPU credits
for distinguisher training, software subscriptions.
Consumables, IIT Bhilai: FPGA boards and target chips for unrolled
implementations, EMFI probe tips, components and cabling.

Travel, IITH (4,00,000): inter-institute visits (two per year), IACR
conference presentation including international travel, standardisation
meetings.
Travel, IIT Bhilai (1,00,000): inter-institute visits and one domestic
conference per year.

Contingency, IITH (3,00,000): short-term research intern stipends, open-access
charges, conference registration, documentation.
Contingency, IIT Bhilai (2,00,000): short-term research intern stipends, spares
and minor hardware for the fault-injection bench, registration fees.

Overhead: 20% of recurring, as per ANRF norms.

## Year-wise budget tables (amounts in INR)

Totals match Table 4 of the technical document. Personnel figures are the
portal's own JRF and RA-I rates; overhead is 20% of each year's recurring.

=== IIT Hyderabad ===
Head                                  Y1          Y2          Y3          Y4         Total
Research Personnel             12,54,000   12,98,400   13,70,400   13,70,400     52,93,200
Consumables                     1,50,000    1,50,000    1,50,000    1,50,000      6,00,000
Travel                            50,000    1,00,000    1,00,000    1,00,000      3,50,000
Contingency                       50,000      50,000    1,00,000    1,00,000      3,00,000
Equipment (non-recurring)      29,43,816           0           0           0     29,43,816
  (RTX PRO 6000 22,53,800 + 2 laptops 2,20,016 + Mac mini 1,20,000
   + Supermicro AS-3015A-I server with EPYC 4565P, 64 GB ECC, 1 TB NVMe
     3,50,000 indicative incl. GST)
Overhead                        portal computes at the 20% setting              13,08,640
Grand Total (excl. overhead)   44,97,816   15,98,400   17,20,400   17,20,400     94,87,016

=== IIT Bhilai ===
Head                                  Y1          Y2          Y3          Y4         Total
Research Personnel             12,54,000   12,98,400   13,70,400   13,70,400     52,93,200
Consumables                     1,00,000    1,00,000    1,00,000    1,00,000      4,00,000
Travel                                 0      50,000      50,000      50,000      1,50,000
Contingency                       50,000      50,000      50,000      50,000      2,00,000
Equipment (non-recurring)      17,45,016           0           0           0     17,45,016
  (2 laptops 2,20,016 + NewAE CW310 Bergen Board (Kintex-7 K410T) 8,50,000 + EM probe set with
   preamplifier 6,75,000; last two indicative incl. GST)
Overhead                        portal computes at the 20% setting              12,08,640
Grand Total (excl. overhead)   31,49,016   14,98,400   15,70,400   15,70,400     77,88,216

=== Project total (incl. overhead) ===   1,97,92,512

Note: the portal draft entered overhead as a flat 3,59,660 / 3,24,660 per
year. If the portal computes overhead itself, let it; only the recurring
lines above need to be typed in.

## Checklist of uploads still pending

- [ ] Technical document PDF (12 pt, max 20 pages, under 10 MB): replace the
      old 7-page upload with the final build of full-proposal.pdf.
- [ ] Bio-data of Co-PI (Dhiman Saha) on the ANRF proforma. PI's is uploaded;
      fix "conduted" -> "conducted" in award 1.
- [ ] Certificate from PI (template CFI_ARG1).
- [ ] Endorsement letter from Head of Institution: IIT Hyderabad, and IIT
      Bhilai since the Co-PI receives a separate budget (template END_ARG1).
- [ ] Plagiarism / AI-generated content / retractions undertaking signed by
      PI and Co-PI (template PUT_ARG1).
- [ ] Optional: LoI from an international or industry collaborator.
- [ ] Summary field: remove the GPU objective wording only if the committee
      objects; otherwise leave the pre-proposal summary unchanged.
- [ ] Deadline: 28 October 2026, 17:00 IST.
