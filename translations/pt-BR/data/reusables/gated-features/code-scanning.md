{% if currentVersion == "free-pro-team@latest" %}{% data variables.product.prodname_code_scanning_capc %} is available for all public repositories, and for private repositories owned by organizations where {% data variables.product.prodname_GH_advanced_security %} is enabled.
{%- elsif currentVersion ver_gt "enterprise-server@3.0" or currentVersion == "github-ae@next" %}{% data variables.product.prodname_code_scanning_capc %} is available for organization-owned repositories where {% data variables.product.prodname_GH_advanced_security %} is enabled.
{%- elsif currentVersion == "github-ae@latest" %}
{% data variables.product.prodname_code_scanning_capc %} is available as part of {% data variables.product.prodname_GH_advanced_security %}, which is free during the beta release.
{%- else %}
{% data variables.product.prodname_code_scanning_capc %} está disponível se você tiver uma licença para {% data variables.product.prodname_GH_advanced_security %}.{% endif %} {% data reusables.advanced-security.more-info-ghas %}
