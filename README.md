# Bastiaansen et al. 2024 — The 4D Human Embryonic Brain Atlas

A **verbatim mirror** of [`10.5281/zenodo.10549081`](https://doi.org/10.5281/zenodo.10549081), redistributed under the terms of the licence the depositors chose. No file has been modified.

## Attribution

> Bastiaansen, Wietske A. P.; Rousian, Melek; Koning, Anton; Niessen, Wiro; de Bakker, Bernadette; Steegers-Theunissen, Regine; Klein, Stefan
>
> Bastiaansen WAP et al. The 4D Human Embryonic Brain Atlas. Zenodo, doi:10.5281/zenodo.10549081. Methods: Computerized Medical Imaging and Graphics 128:102702 (2026).
>
> DOI: [10.5281/zenodo.10549081](https://doi.org/10.5281/zenodo.10549081) — licensed **CC BY-NC 4.0**

Licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by/4.0/); see [`LICENSE`](LICENSE). You may share and adapt this material for any purpose, including commercially, provided you give appropriate credit, link to the licence and indicate if changes were made. **This mirror makes no changes.**

## What this is

Thirty-five NIfTI volumes, one per gestational day from day 56 to day 90, built from 831 3D ultrasound scans of 402 pregnancies in the Rotterdam Periconceptional Cohort by deep-learning groupwise registration. The only in vivo, day-resolved human developmental geometry this project has found; everything else it holds is fixed and sectioned material.

## NonCommercial and NoDerivatives: what that means here

This licence **permits** what this repository does — reproducing and sharing the material verbatim, with attribution, for non-commercial purposes. It withholds two things, and both matter:

- **No commercial use.** Not by this mirror and not by you.
- **No distributing adaptations.** You may convert, re-mesh or re-segment your own copy — conversion is not distribution — but you may not publish the result. NoDerivatives withholds exactly that.

**This material cannot be bundled into AGPL-licensed software.** The project that maintains this mirror is AGPL-3.0-or-later, which guarantees downstream recipients the right to use and modify it commercially; NonCommercial withholds that right, so the two licences cannot coexist in one distribution. That is why this is a standalone repository and why no code depends on these files being present.

## Provenance of the material

Derived from routine clinical 3D ultrasound of ongoing pregnancies in a cohort study, so no embryonic tissue was collected for it. Cohort ethics are stated in the methods paper rather than in the deposit.

## Contents

35 file(s), 335.4 MB total.

| File | Size | SHA-256 |
| --- | --- | --- |
| `data/atlas_72.nii.gz` | 9.6 MB | `df5d66450c031598…` |
| `data/atlas_75.nii.gz` | 9.5 MB | `3c91fbfefc68138e…` |
| `data/atlas_84.nii.gz` | 9.5 MB | `3f9bb24e80c458e6…` |
| `data/atlas_59.nii.gz` | 9.7 MB | `769eab3db8ede62f…` |
| `data/atlas_82.nii.gz` | 9.5 MB | `a5452b95b8ffd53f…` |
| `data/atlas_57.nii.gz` | 9.7 MB | `14d4ec59efe63a4e…` |
| `data/atlas_60.nii.gz` | 9.7 MB | `61b87a1bbeeee8cb…` |
| `data/atlas_65.nii.gz` | 9.6 MB | `a320374fe56e4ab1…` |
| `data/atlas_61.nii.gz` | 9.7 MB | `d38701e3a1258ae8…` |
| `data/atlas_64.nii.gz` | 9.6 MB | `8aa63d59d89e8209…` |
| `data/atlas_67.nii.gz` | 9.6 MB | `d2be706eed0e9ef7…` |
| `data/atlas_86.nii.gz` | 9.5 MB | `0f392c1f20998772…` |
| `data/atlas_66.nii.gz` | 9.6 MB | `7dd05ea5a232af43…` |
| `data/atlas_70.nii.gz` | 9.6 MB | `4a220e2312d7c35b…` |
| `data/atlas_85.nii.gz` | 9.5 MB | `e61b564aa2cc1a99…` |
| `data/atlas_90.nii.gz` | 9.5 MB | `bb4c60efb284d5b9…` |
| `data/atlas_68.nii.gz` | 9.6 MB | `2a29805c6718a5d6…` |
| `data/atlas_69.nii.gz` | 9.6 MB | `903f8d08e79f30b5…` |
| `data/atlas_89.nii.gz` | 9.5 MB | `a56a933d018b2748…` |
| `data/atlas_71.nii.gz` | 9.6 MB | `43427396f00ecdd7…` |
| `data/atlas_73.nii.gz` | 9.6 MB | `c5f2347a798d5695…` |
| `data/atlas_74.nii.gz` | 9.6 MB | `1f27fdd97092d27e…` |
| `data/atlas_76.nii.gz` | 9.5 MB | `864c6713bb12c0af…` |
| `data/atlas_77.nii.gz` | 9.5 MB | `100b98a801898eac…` |
| `data/atlas_80.nii.gz` | 9.5 MB | `9c572e552ce85e53…` |
| `data/atlas_88.nii.gz` | 9.5 MB | `b8c8f4c565b9be79…` |
| `data/atlas_78.nii.gz` | 9.5 MB | `ff17ec1a62117466…` |
| `data/atlas_79.nii.gz` | 9.5 MB | `0e31041c02a6463e…` |
| `data/atlas_83.nii.gz` | 9.5 MB | `0ebd235cc726b32f…` |
| `data/atlas_56.nii.gz` | 9.7 MB | `a19c3f6b1e62d2b9…` |
| `data/atlas_62.nii.gz` | 9.7 MB | `3241036313bcf807…` |
| `data/atlas_63.nii.gz` | 9.7 MB | `2db89d67c43e89c7…` |
| `data/atlas_58.nii.gz` | 9.7 MB | `5e80f9b1373d4d15…` |
| `data/atlas_81.nii.gz` | 9.5 MB | `7387866201318de0…` |
| `data/atlas_87.nii.gz` | 9.5 MB | `54599dfd0d088bef…` |

Full checksums, original filenames and the source article id for every file are in [`MANIFEST.json`](MANIFEST.json).

## Notes for anyone using this

- IMPORTANT: the NIfTI headers carry no physical scale. pixdim is (1,1,1), xyzt_units is 0, qform_code is 0 and the sform is a bare identity matrix — one byte-identical header signature across all 35 files. A 128 mm cube is not an embryonic brain. The true isotropic voxel size is day-dependent and appears only in the methods paper: S(t) = -0.3606 + 0.0084t mm, so 0.11 mm at day 56 widening to 0.40 mm at day 90. Anything trusting pixdim is out by an order of magnitude.
- Consequently the volumes share a common frame in voxel-index space only, not in physical space.
- The files are an intensity template, not a segmentation: every one of the 2,097,152 voxels is nonzero in every volume. The manual ventricle, choroid-plexus and cerebellum segmentations described in the paper are not included.
- Days are gestational age on the last-menstrual-period convention, roughly 14 days ahead of a post-fertilisation clock. Day 56 is post-fertilisation day ~42, around Carnegie stage 16/17, so the series overlaps the embryonic period rather than beginning after it.
- Read with tools/nifti.ts; tools/probe-nifti.ts tabulates the whole series.

## Verifying the mirror

```sh
# every file, against the manifest
python3 -c "import json,hashlib,pathlib;m=json.load(open('MANIFEST.json'));[print(('ok  ' if hashlib.sha256(pathlib.Path(f['path']).read_bytes()).hexdigest()==f['sha256'] else 'BAD ')+f['path']) for f in m['files'] if pathlib.Path(f['path']).exists()]"
```

---

Mirrored 2026-11-22 by `tools/mirror.ts` from [embryogenesis](https://github.com/embryogenesis/embryogenesis). The licence of each source record was checked against the live Zenodo metadata (`metadata.license.id`) before download. A record stating no licence aborts the mirror rather than defaulting to one.
