## Steps to reproduce [issue 2541](https://github.com/sveltejs/language-tools/issues/2541)

1. Make sure you have installed the latest version of the Dev Containers extension (ms-vscode-remote.remote-containers)
2. Run the command `Dev Containers: Reopen in Container`
3. Open apps/web/src/lib/TestComponent.svelte
4. Try to trigger import completion (CTRL + Space) for `NotificationTy` (line 5)

It may work the first time, but after that it stops working completely.
