A repository to reproduce [Argo CD issue #15566](https://github.com/argoproj/argo-cd/issues/15566)

Apply the Argo CD Application CRD `argocd-app.yaml` from the `main` branch,
then change `.spec.targetRevision` to `null-value-test` to trigger the issue
described in the ticket.
