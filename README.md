# GitHub Actions Practice 🚀

A dedicated execution environment for testing CI/CD pipelines, automated workflows, and GitHub Actions primitives as part of the **#90DaysProductionReadyDevOpsSREJourney**.

## 🧠 Core CI/CD Concepts Explored

*   **Workflow Anatomy:** Provisioning isolated runners (`ubuntu-latest`, `windows-latest`) and structuring multi-step jobs.
*   **Event Triggers:** 
    *   `push`: Automated execution on branch updates.
    *   `pull_request`: Quality gates for code merging (`pr-check.yml`).
    *   `schedule`: Cron-based task execution.
    *   `workflow_dispatch`: Manual triggers with custom inputs (`manual.yml`).
*   **Matrix Builds:** Running concurrent tests across multiple operating systems and runtime versions while controlling `fail-fast` behavior (`matrix.yml`).
*   **Marketplace Actions:** Leveraging reusable community actions like `actions/checkout@v4`.
*   **Incident Debugging:** Testing non-zero exit codes and analyzing raw `stderr` runner logs to understand failure states.

## 📂 Repository Structure

All active pipeline configurations are located in the `.github/workflows/` directory. For full theoretical documentation, architectural diagrams, and daily notes, refer to the [Main Journey Repository](https://github.com/NB11-ML/Production-Ready-DevOps-SRE-Journey).
