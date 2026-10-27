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

## Response to Referee Comments on the Pre-Proposal

We thank the committee and the reviewers for their positive assessment. The
committee asked for "clearly delineated objectives that will move the project
along at a steady pace". The full proposal responds as follows.

1. The five objectives of Section 2 are now each stated with a hypothesis and
   numbered, measurable success metrics against named baselines (ARADI, ChiLow,
   SCARF, QARMAv2; PRINCEv2 and ARADI for the design work).
2. The research approach of Section 4 is organised into six work packages
   (Table 1), each with a lead institute, the objective it serves, its months
   and its deliverables, together with a risk and mitigation list.
3. Section 6 gives a 48-month Gantt chart with eight milestones, each tied to a
   deliverable of Section 5. Four milestones fall in the first three years and
   serve as checkpoints for the phased release of support.
4. Section 3.4 summarises the preliminary results on which each work package
   starts, so that progress in year one does not depend on new groundwork.

No objective of the pre-proposal has been dropped or changed. The GPU-oriented
cryptanalysis and the indigenous cipher design listed in the pre-proposal
appear as part of Objective 1 and Objective 4 respectively.

## Any other relevant information

- The budget has been revised from the working draft to respect the ARG
  ceilings: travel Rs 5 lakh and contingency Rs 5 lakh for the whole project.
- No equipment is requested. The fault-injection bench and GPU workstations at
  IIT Bhilai already exist; an EMFI extension is being funded separately by the
  institute.
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
Head                          Y1          Y2          Y3          Y4         Total
Research Personnel     12,54,000   12,98,400   13,70,400   13,70,400     52,93,200
Consumables             1,50,000    1,50,000    1,50,000    1,50,000      6,00,000
Travel                  1,00,000    1,00,000    1,00,000    1,00,000      4,00,000
Contingency               75,000      75,000      75,000      75,000      3,00,000
Overhead (20%)          3,15,800    3,24,680    3,39,080    3,39,080     13,18,640
Grand Total            18,94,800   19,48,080   20,34,480   20,34,480     79,11,840

=== IIT Bhilai ===
Head                          Y1          Y2          Y3          Y4         Total
Research Personnel     12,54,000   12,98,400   13,70,400   13,70,400     52,93,200
Consumables             1,00,000    1,00,000    1,00,000    1,00,000      4,00,000
Travel                    25,000      25,000      25,000      25,000      1,00,000
Contingency               50,000      50,000      50,000      50,000      2,00,000
Overhead (20%)          2,85,800    2,94,680    3,09,080    3,09,080     11,98,640
Grand Total            17,14,800   17,68,080   18,54,480   18,54,480     71,91,840

=== Project total ===
                       36,09,600   37,16,160   38,88,960   38,88,960   1,51,03,680

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
