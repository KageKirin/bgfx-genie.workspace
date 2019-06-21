# -----------------------------------------------------------------------------
# DEPS file for bgfx-genie.workspace
# ========================================
# -----------------------------------------------------------------------------
# This file is used to manage the dependencies of the bgfx-genie.workspace repo.
#
# It is used by gclient to determine what version of each dependency to check
# out, and where.
#
# For more information, please refer to the official documentation:
#   https://sites.google.com/a/chromium.org/dev/developers/how-tos/get-the-code
#
# When adding a new dependency, please update the top-level .gitignore file
# to list the dependency's destination directory.
#
# -----------------------------------------------------------------------------
# Rolling deps
# -----------------------------------------------------------------------------
# All repositories in this file are git-based
# To update the revision that gclient pulls for a given dependency:
#
#  1. Create and switch to a new branch
#  git new-branch depsroll
#  2. Run roll-dep (provided by depot_tools) giving the dep's path and optionally
#     a regex that will match the line in this file that contains the current
#     revision. The script ALWAYS rolls the dependency to the latest revision
#     in origin/master. The path for the dep should start with src/.
#     roll-dep src/third_party/foo_package/src foo_package.git
#  3. You should now have a modified DEPS file; commit and upload as normal
#     git commit -a
#     git ps <branch>
#     hub create-pull-request
# -----------------------------------------------------------------------------


use_relative_paths = True

hooks = []

recursedeps = []

vars = {
  # ---------------------------------------------------------------------------
  # Non-versioning vars
  # -------------------
  # variables used for other remote url etc
  # ---------------------------------------------------------------------------

  # ---------------------------------------------------------------------------
  # Versioning vars
  # ---------------
  # revision hash, tag or branch (preferred for readability)
  # sorted alphabetically to index into sections below
  # ---------------------------------------------------------------------------
  # keep
  # this
  # line
  'bgfx_revision': '',
  # keep
  # this
  # line
  'bimg_revision': '',
  # keep
  # this
  # line
  'bnet_revision': '',
  # keep
  # this
  # line
  'bx_revision': '',
  # keep
  # this
  # line
  'genie_revision': '',
  # keep
  # this
  # line
  # ---------------------------------------------------------------------------
}

deps = {
  # ---------------------------------------------------------------------------
  ## repos to fetch
  ## entry following this pattern
  ## 'path': 'repo-url.git@{repo_revision}'
  # ---------------------------------------------------------------------------
  # keep
  # this
  # line
  'bgfx': 'git@github.com:bkaradzic/bgfx.git@{bgfx_revision}',
  # keep
  # this
  # line
  'bimg': 'git@github.com:bkaradzic/bimg.git@{bimg_revision}',
  # keep
  # this
  # line
  'bnet': 'git@github.com:bkaradzic/bnet.git@{bnet_revision}',
  # keep
  # this
  # line
  'bx': 'git@github.com:bkaradzic/bx.git@{bx_revision}',
  # keep
  # this
  # line
  'GENie': 'git@github.com:bkaradzic/GENie.git@{genie_revision}',
  # keep
  # this
  # line
  # -----------------------------------------------------------------------------
}
