
Changelog
=========

`1.15.5 <https://github.com/saltstack-formulas/epel-formula/compare/v1.15.4...v1.15.5>`_ (2020-12-25)
---------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **map.jinja:** update EL6 URLs (\ `7a87d42 <https://github.com/saltstack-formulas/epel-formula/commit/7a87d427ea2b1f746f9028d0fa670138780559e0>`_\ )

`1.15.4 <https://github.com/saltstack-formulas/epel-formula/compare/v1.15.3...v1.15.4>`_ (2020-12-25)
---------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **map.jinja:** update GPG url (\ `a5e6161 <https://github.com/saltstack-formulas/epel-formula/commit/a5e61611c03832b2dc0a25af7f31d5d4c55f2896>`_\ )

`1.15.3 <https://github.com/saltstack-formulas/epel-formula/compare/v1.15.2...v1.15.3>`_ (2020-12-22)
---------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **map.jinja:** update to ``epel-release-8-10.el8.noarch.rpm`` (\ `82f8d68 <https://github.com/saltstack-formulas/epel-formula/commit/82f8d683199cd6e79fe30ccbd73ec77f3cca4ef8>`_\ )
* osmajorrelease is int instead of str since 2017.7.1 (\ `5fdd1fc <https://github.com/saltstack-formulas/epel-formula/commit/5fdd1fc054af4f156fae7c20ba191e051938eef8>`_\ ), closes `/github.com/saltstack/salt/blob/v2017.7.1/salt/grains/core.py#L1675 <https://github.com//github.com/saltstack/salt/blob/v2017.7.1/salt/grains/core.py/issues/L1675>`_

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **commitlint:** ensure ``upstream/master`` uses main repo URL [skip ci] (\ `ae613cd <https://github.com/saltstack-formulas/epel-formula/commit/ae613cddddc248b1de97d5e9d0125d22435432d4>`_\ )
* **gitlab-ci:** add ``rubocop`` linter (with ``allow_failure``\ ) [skip ci] (\ `858f8f0 <https://github.com/saltstack-formulas/epel-formula/commit/858f8f08c5a63459bac7c329b6cf1e86ac2aa428>`_\ )

`1.15.2 <https://github.com/saltstack-formulas/epel-formula/compare/v1.15.1...v1.15.2>`_ (2020-12-16)
---------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **map.jinja:** update link to ``rpm`` for ``EPEL-7`` (\ `b778c62 <https://github.com/saltstack-formulas/epel-formula/commit/b778c629170be41abcc110779b34c2ddd319b920>`_\ )
* **map.jinja:** update link to ``rpm`` for ``EPEL-8`` (\ `1ad5806 <https://github.com/saltstack-formulas/epel-formula/commit/1ad5806ecd2764ac0b8212afd7a0af78b3c799a4>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **gemfile.lock:** add to repo with updated ``Gemfile`` [skip ci] (\ `cc00467 <https://github.com/saltstack-formulas/epel-formula/commit/cc0046735698e6763be5298fcf4ee3713d6f7281>`_\ )
* **gitlab-ci:** use GitLab CI as Travis CI replacement (\ `3cf58d8 <https://github.com/saltstack-formulas/epel-formula/commit/3cf58d8b277deec223fe0c3665221e53accc53c0>`_\ )
* **kitchen:** use ``saltimages`` Docker Hub where available [skip ci] (\ `ace478e <https://github.com/saltstack-formulas/epel-formula/commit/ace478e4b8413a423390ee38af5fe815b1fdef9b>`_\ )
* **pre-commit:** add to formula [skip ci] (\ `f57867a <https://github.com/saltstack-formulas/epel-formula/commit/f57867a99ba6949517abd1916c32ea7b37512adb>`_\ )
* **pre-commit:** enable/disable ``rstcheck`` as relevant [skip ci] (\ `a160c4a <https://github.com/saltstack-formulas/epel-formula/commit/a160c4a16c868b591f22ea267dfef3ce42e0b8c9>`_\ )
* **pre-commit:** finalise ``rstcheck`` configuration [skip ci] (\ `8039f7c <https://github.com/saltstack-formulas/epel-formula/commit/8039f7cbbbef5e428a4c15a58f3ed8ce176e35a1>`_\ )
* **travis:** add notifications => zulip [skip ci] (\ `d90fb30 <https://github.com/saltstack-formulas/epel-formula/commit/d90fb30a0af6bcd447527a55ce7ded21323f05af>`_\ )
* **workflows/commitlint:** add to repo [skip ci] (\ `8be296e <https://github.com/saltstack-formulas/epel-formula/commit/8be296eff1df2247ae6d7f4bd6d04e697d416cbe>`_\ )

Tests
^^^^^


* **packages_spec:** refactor to check first part of version number only (\ `a4f2f2c <https://github.com/saltstack-formulas/epel-formula/commit/a4f2f2c532ba316d6cce2516760c710c5cb045ec>`_\ )

`1.15.1 <https://github.com/saltstack-formulas/epel-formula/compare/v1.15.0...v1.15.1>`_ (2020-02-13)
---------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **map.jinja:** update link to ``rpm`` for ``EPEL-8`` (\ `3e90e0d <https://github.com/saltstack-formulas/epel-formula/commit/3e90e0de36217ab6d15bc03dc907524ab49d7727>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **gemfile:** restrict ``train`` gem version until upstream fix [skip ci] (\ `bddcd80 <https://github.com/saltstack-formulas/epel-formula/commit/bddcd80a2b2c59846f26cc11cd855199837ec8bd>`_\ )
* **kitchen:** avoid using bootstrap for ``master`` instances [skip ci] (\ `30ade3d <https://github.com/saltstack-formulas/epel-formula/commit/30ade3d539d2b92c1ac0521952824c0221c9602d>`_\ )
* **kitchen:** use ``develop`` image until ``master`` is ready (\ ``amazonlinux``\ ) [skip ci] (\ `5db2344 <https://github.com/saltstack-formulas/epel-formula/commit/5db23441832b058f2b4c6b4f2ddc757ab4647f50>`_\ )
* **kitchen:** use ``provision_command`` for ``amazonlinux-1`` images (\ `2cfcfde <https://github.com/saltstack-formulas/epel-formula/commit/2cfcfde545303a455a662854b506d2cb36588a9d>`_\ ), closes `/github.com/saltstack-formulas/vault-formula/pull/50#pullrequestreview-312037893 <https://github.com//github.com/saltstack-formulas/vault-formula/pull/50/issues/pullrequestreview-312037893>`_
* **kitchen:** use ``stable`` for ``amazonlinux-1`` bootstrap [skip ci] (\ `472434b <https://github.com/saltstack-formulas/epel-formula/commit/472434b14e6861f6a17f297b8c7fd501dd4cae4a>`_\ )
* **kitchen+travis:** use bootstrapped ``amazonlinux-1`` images [skip ci] (\ `37d2fc6 <https://github.com/saltstack-formulas/epel-formula/commit/37d2fc6ff4089ab173766aeac87964987e38c11e>`_\ )
* **travis:** apply changes from build config validation [skip ci] (\ `904b4fc <https://github.com/saltstack-formulas/epel-formula/commit/904b4fc236b4a93b8d5a6feeb682a99b958f30cb>`_\ )
* **travis:** opt-in to ``dpl v2`` to complete build config validation [skip ci] (\ `5fa5251 <https://github.com/saltstack-formulas/epel-formula/commit/5fa5251c74eb9dccd1fcd0e1ca5038e34f075a4d>`_\ )
* **travis:** quote pathspecs used with ``git ls-files`` [skip ci] (\ `6d28624 <https://github.com/saltstack-formulas/epel-formula/commit/6d286241e01658611dd247dce656157f49afddeb>`_\ )
* **travis:** run ``shellcheck`` during lint job [skip ci] (\ `8491178 <https://github.com/saltstack-formulas/epel-formula/commit/8491178dcd9bab4f5419fcc5ade0a9f38f1a4281>`_\ )
* **travis:** use ``major.minor`` for ``semantic-release`` version [skip ci] (\ `f7f2342 <https://github.com/saltstack-formulas/epel-formula/commit/f7f2342a397e699b65053a35dba0b3c75ccfbce7>`_\ )
* **travis:** use build config validation (beta) [skip ci] (\ `ecab107 <https://github.com/saltstack-formulas/epel-formula/commit/ecab107ae92470a8e6d53b1dc18d76d1c4f3b345>`_\ )

`1.15.0 <https://github.com/saltstack-formulas/epel-formula/compare/v1.14.1...v1.15.0>`_ (2019-11-03)
---------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **map.jinja:** fix typo ``osmajorreleaes`` (\ `4f9b8d4 <https://github.com/saltstack-formulas/epel-formula/commit/4f9b8d46ee1c6f890e6f5baf824cfa42853e0d91>`_\ )
* **map.jinja:** update ``epel/8`` package link (\ `474ac85 <https://github.com/saltstack-formulas/epel-formula/commit/474ac8588d87f782174a179fa4ae4aad6bb3e401>`_\ )
* **yamllint:** fix all errors (\ `d670ff7 <https://github.com/saltstack-formulas/epel-formula/commit/d670ff7a9327637a6baac8a9bf0aaa6ded564494>`_\ )

Code Refactoring
^^^^^^^^^^^^^^^^


* **map.jinja:** use consistent chronological ordering of releases (\ `27a2c3b <https://github.com/saltstack-formulas/epel-formula/commit/27a2c3b2703b5e4d604e51ec99b3885647835b14>`_\ )

Documentation
^^^^^^^^^^^^^


* **readme:** modify according to standard structure (\ `1892879 <https://github.com/saltstack-formulas/epel-formula/commit/1892879754723444ac73948653d39129da9b08fd>`_\ ), closes `/github.com/saltstack-formulas/epel-formula/pull/52#issuecomment-547653363 <https://github.com//github.com/saltstack-formulas/epel-formula/pull/52/issues/issuecomment-547653363>`_
* **readme:** move to ``docs/`` directory (\ `eb8b8af <https://github.com/saltstack-formulas/epel-formula/commit/eb8b8afafd2810d1a3a6e83ed3d24cb36fc67647>`_\ )

Features
^^^^^^^^


* **amazon:** use major release ``2`` as the default (\ `93654e9 <https://github.com/saltstack-formulas/epel-formula/commit/93654e91059878210968b56d82a94a0d76912d39>`_\ )
* **semantic-release:** implement for this formula (\ `6379098 <https://github.com/saltstack-formulas/epel-formula/commit/63790984afed54d9e0b8f6535e89ddb5f048b487>`_\ )

Styles
^^^^^^


* **map.jinja:** add a space after the colon (\ `cf14db0 <https://github.com/saltstack-formulas/epel-formula/commit/cf14db0a6ebc0de31a8c71815814fb819babb3b7>`_\ )

Tests
^^^^^


* **inspec:** provide tests for the repo package and config (\ `35b98d5 <https://github.com/saltstack-formulas/epel-formula/commit/35b98d55c8ea4b786a889e33bc0418d2f2d87dbe>`_\ )
* **pillar:** add test pillar (\ `0efbe3a <https://github.com/saltstack-formulas/epel-formula/commit/0efbe3a743ba8890f5841ec4295fee9538400674>`_\ )
