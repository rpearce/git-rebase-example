# git-rebase-example

Dropping the bass with git rebase.

<figure>
  <img
    alt=""
    height="320"
    loading="lazy"
    src="https://res.cloudinary.com/practicaldev/image/fetch/s--hoIMx6MM--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_800/https://thepracticaldev.s3.amazonaws.com/i/7qzryt6xov0hcsmek83n.jpg"
    width="auto"
  />
  <figcaption>
    <i>Art from <a href="https://dev.to/maxwell_dev/the-git-rebase-introduction-i-wish-id-had">The Git Rebase Introduction I Wish I Had</a></i>
  </figcaption>
</figure>

## The plan

Dive right in!

1. Merging `main` into our feature branch vs rebasing `main`
   * What about conflicts?!?
1. Simple amending of commits with `git commit --amend`
1. Fixup, squash, reword, and delete our garbage commits with `git rebase -i`
1. A word about `git push`'s `--force` vs `--force-with-lease`
1. Survival tip: assume everyone is a secret rebaser & force pusher
   * `git pull --rebase origin/the-branch`
   * `git config --global pull.rebase true`, or in `.gitconfig`:
      ```
      [pull]
        rebase = true
      ```
1. Branching off branches, keeping up with rebasing, parent branch gets merged
   to `main`, and what now? `git rebase --onto` ftw
1. Rebasing Etiquette, or: How to Not Make People Hate You

## Links

* https://git-scm.com/docs/git-rebase
* https://git-scm.com/book/en/v2/Git-Branching-Rebasing
* https://docs.github.com/en/get-started/using-git/about-git-rebase
* https://jvns.ca/blog/2023/11/06/rebasing-what-can-go-wrong-/
* https://git-scm.com/docs/git-push
* https://git-scm.com/docs/git-pull
* https://git-scm.com/docs/git-commit
