# Setup SLURM

Sets up a [SLURM](https://slurm.schedmd.com) controller and node (on the same machine) for testing purposes.
This action has been tested with `ubuntu-latest`.

## Usage

```yaml
      - name: Setup SLURM
        uses: cyderize/action-setup-slurm@v1
      - name: Run SLURM job
        run: |
          srun sleep 10
```
