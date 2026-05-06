# DLAV Project

Each phase lives in its own notebook under `final_project/`. Run `uv sync && uv run jupyter lab`, open the notebook, and run the cells top-to-bottom: each one downloads its data, trains the model, and writes a `submission_phaseN.csv` ready for the corresponding Kaggle leaderboard.

## Phase 1
`final_project/DLAV_Phase1.ipynb` — basic end-to-end planner (camera + driving command + history). Saves `phase1_model.pth` and writes `submission_phase1.csv`.

## Phase 2
`final_project/DLAV_Phase2.ipynb` — perception-aware planner with auxiliary depth and semantic segmentation tasks. Writes `submission_phase2.csv`.

## Phase 3
`final_project/DLAV_Phase3.ipynb` — sim-to-real generalization (no depth/semantic labels available; relies on data augmentation). Writes `submission_phase3.csv`.
