
# install-pinned/maturin-with-zig
<!-- !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!! -->
<!-- ⚠️auto-generated from init.py, do not edit manually ⚠️-->
<!-- !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!! -->

![](https://shields.io/badge/python-3.7%20%7C%203.8%20%7C%203.9%20%7C%203.10%20%7C%203.11-blue)

Securely install the latest [maturin[zig]](https://pypi.org/project/maturin/) release from PyPI.

This action installs a pinned version of **maturin[zig]** and all its dependencies,         making sure that file hashes match. Pinning your dependencies:

 1. Stops software supply chain attacks.
 2. Makes sure your CI does not break unexpectedly.

## Usage

In your GitHub Actions workflow, use this action like so:

```yaml
      - name: Install maturin[zig] from PyPI
        uses: install-pinned/maturin-with-zig@0bcef485a460fe61d0704f3b69319b4885b70e80  # 0.14.3
```

You can [set up Dependabot](https://docs.github.com/en/code-security/dependabot/working-with-dependabot/keeping-your-actions-up-to-date-with-dependabot#example-dependabotyml-file-for-github-actions)
so that your pins are updated regularly.

## Alternatives

This action is a relatively simple wrapper around the fantastic [pip-tools](https://pip-tools.rtfd.io)         and is most useful if there is no existing `requirements.txt`/`poetry.lock`/... infrastructure in place.         If you already pin all your dependencies in a single place, you don't need it!

## More Details

See the [@install-pinned README](https://github.com/install-pinned) for details.
