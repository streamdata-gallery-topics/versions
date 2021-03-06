---
name: Google Cloud Machine Learning Engine
x-slug: google-cloud-machine-learning-engine
description: Google Cloud Machine Learning Engine is a managed service that enables
  you to easily build machine learning models, that work on any type of data, of any
  size. Create your model with the powerful TensorFlow framework that powers many
  Google products, from Google Photos to Google Cloud Speech. Build models of any
  size with our managed scalable infrastructure. Your trained model is immediately
  available for use with our global prediction platform that can support thousands
  of users and TBs of data.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Versions
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Machine Learning Engine - Delete Model Version
  x-api-slug: v1name-delete
  description: |-
    Deletes a model version.

    Each model can have multiple versions deployed and in use at any given
    time. Use this method to remove a single version.

    Note: You cannot delete the version that is set as the default version
    of the model unless it is the only remaining version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1name-delete-openapi.md
- name: Google Cloud Machine Learning Engine - Get Model Version
  x-api-slug: v1name-get
  description: |-
    Gets information about a model version.

    Models can have multiple versions. You can call
    [projects.models.versions.list](/ml/reference/rest/v1/projects.models.versions/list)
    to get the same information that this method returns for all of the
    versions of a model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1name-get-openapi.md
- name: Google Cloud Machine Learning Engine - Set Default Version
  x-api-slug: v1namesetdefault-post
  description: |-
    Designates a version to be the default for the model.

    The default version is used for prediction requests made against the model
    that don't specify a version.

    The first version to be created for a model is automatically set as the
    default. You must make any subsequent changes to the default version
    setting manually using this method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1namesetdefault-post-openapi.md
- name: Google Cloud Machine Learning Engine - Get Version
  x-api-slug: v1parentversions-get
  description: |-
    Gets basic information about all the versions of a model.

    If you expect that a model has a lot of versions, or if you need to handle
    only a limited number of results at a time, you can request that the list
    be retrieved in batches (called pages):
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1parentversions-get-openapi.md
- name: Google Cloud Machine Learning Engine - Create Version
  x-api-slug: v1parentversions-post
  description: |-
    Creates a new version of a model from a trained TensorFlow model.

    If the version created in the cloud by this call is the first deployed
    version of the specified model, it will be made the default version of the
    model. When you add a version to a model that already has one or more
    versions, the default version does not automatically change. If you want a
    new version to be the default, you must call
    [projects.models.versions.setDefault](/ml/reference/rest/v1/projects.models.versions/setDefault).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1parentversions-post-openapi.md
- name: Google Cloud Machine Learning Engine - Delete Model Version
  x-api-slug: v1name-delete
  description: |-
    Deletes a model version.

    Each model can have multiple versions deployed and in use at any given
    time. Use this method to remove a single version.

    Note: You cannot delete the version that is set as the default version
    of the model unless it is the only remaining version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1name-delete-openapi.md
- name: Google Cloud Machine Learning Engine - Get Model Version
  x-api-slug: v1name-get
  description: |-
    Gets information about a model version.

    Models can have multiple versions. You can call
    [projects.models.versions.list](/ml/reference/rest/v1/projects.models.versions/list)
    to get the same information that this method returns for all of the
    versions of a model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1name-get-openapi.md
- name: Google Cloud Machine Learning Engine - Set Default Version
  x-api-slug: v1namesetdefault-post
  description: |-
    Designates a version to be the default for the model.

    The default version is used for prediction requests made against the model
    that don't specify a version.

    The first version to be created for a model is automatically set as the
    default. You must make any subsequent changes to the default version
    setting manually using this method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1namesetdefault-post-openapi.md
- name: Google Cloud Machine Learning Engine - Get Version
  x-api-slug: v1parentversions-get
  description: |-
    Gets basic information about all the versions of a model.

    If you expect that a model has a lot of versions, or if you need to handle
    only a limited number of results at a time, you can request that the list
    be retrieved in batches (called pages):
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1parentversions-get-openapi.md
- name: Google Cloud Machine Learning Engine - Create Version
  x-api-slug: v1parentversions-post
  description: |-
    Creates a new version of a model from a trained TensorFlow model.

    If the version created in the cloud by this call is the first deployed
    version of the specified model, it will be made the default version of the
    model. When you add a version to a model that already has one or more
    versions, the default version does not automatically change. If you want a
    new version to be the default, you must call
    [projects.models.versions.setDefault](/ml/reference/rest/v1/projects.models.versions/setDefault).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1parentversions-post-openapi.md
- name: Google Cloud Machine Learning Engine - Create Version
  x-api-slug: v1parentversions-post
  description: |-
    Creates a new version of a model from a trained TensorFlow model.

    If the version created in the cloud by this call is the first deployed
    version of the specified model, it will be made the default version of the
    model. When you add a version to a model that already has one or more
    versions, the default version does not automatically change. If you want a
    new version to be the default, you must call
    [projects.models.versions.setDefault](/ml/reference/rest/v1/projects.models.versions/setDefault).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1parentversions-post-openapi.md
- name: Google Cloud Machine Learning Engine - Create Version
  x-api-slug: v1parentversions-post
  description: |-
    Creates a new version of a model from a trained TensorFlow model.

    If the version created in the cloud by this call is the first deployed
    version of the specified model, it will be made the default version of the
    model. When you add a version to a model that already has one or more
    versions, the default version does not automatically change. If you want a
    new version to be the default, you must call
    [projects.models.versions.setDefault](/ml/reference/rest/v1/projects.models.versions/setDefault).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1parentversions-post-openapi.md
- name: Google Cloud Machine Learning Engine - Get Version
  x-api-slug: v1parentversions-get
  description: |-
    Gets basic information about all the versions of a model.

    If you expect that a model has a lot of versions, or if you need to handle
    only a limited number of results at a time, you can request that the list
    be retrieved in batches (called pages):
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1parentversions-get-openapi.md
- name: Google Cloud Machine Learning Engine - Get Version
  x-api-slug: v1parentversions-get
  description: |-
    Gets basic information about all the versions of a model.

    If you expect that a model has a lot of versions, or if you need to handle
    only a limited number of results at a time, you can request that the list
    be retrieved in batches (called pages):
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1parentversions-get-openapi.md
- name: Google Cloud Machine Learning Engine - Create Version
  x-api-slug: v1parentversions-post
  description: |-
    Creates a new version of a model from a trained TensorFlow model.

    If the version created in the cloud by this call is the first deployed
    version of the specified model, it will be made the default version of the
    model. When you add a version to a model that already has one or more
    versions, the default version does not automatically change. If you want a
    new version to be the default, you must call
    [projects.models.versions.setDefault](/ml/reference/rest/v1/projects.models.versions/setDefault).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1parentversions-post-openapi.md
- name: Google Cloud Machine Learning Engine - Set Default Version
  x-api-slug: v1namesetdefault-post
  description: |-
    Designates a version to be the default for the model.

    The default version is used for prediction requests made against the model
    that don't specify a version.

    The first version to be created for a model is automatically set as the
    default. You must make any subsequent changes to the default version
    setting manually using this method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1namesetdefault-post-openapi.md
- name: Google Cloud Machine Learning Engine - Set Default Version
  x-api-slug: v1namesetdefault-post
  description: |-
    Designates a version to be the default for the model.

    The default version is used for prediction requests made against the model
    that don't specify a version.

    The first version to be created for a model is automatically set as the
    default. You must make any subsequent changes to the default version
    setting manually using this method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1namesetdefault-post-openapi.md
- name: Google Cloud Machine Learning Engine - Get Version
  x-api-slug: v1parentversions-get
  description: |-
    Gets basic information about all the versions of a model.

    If you expect that a model has a lot of versions, or if you need to handle
    only a limited number of results at a time, you can request that the list
    be retrieved in batches (called pages):
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1parentversions-get-openapi.md
- name: Google Cloud Machine Learning Engine - Get Model Version
  x-api-slug: v1name-get
  description: |-
    Gets information about a model version.

    Models can have multiple versions. You can call
    [projects.models.versions.list](/ml/reference/rest/v1/projects.models.versions/list)
    to get the same information that this method returns for all of the
    versions of a model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1name-get-openapi.md
- name: Google Cloud Machine Learning Engine - Get Model Version
  x-api-slug: v1name-get
  description: |-
    Gets information about a model version.

    Models can have multiple versions. You can call
    [projects.models.versions.list](/ml/reference/rest/v1/projects.models.versions/list)
    to get the same information that this method returns for all of the
    versions of a model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1name-get-openapi.md
- name: Google Cloud Machine Learning Engine - Set Default Version
  x-api-slug: v1namesetdefault-post
  description: |-
    Designates a version to be the default for the model.

    The default version is used for prediction requests made against the model
    that don't specify a version.

    The first version to be created for a model is automatically set as the
    default. You must make any subsequent changes to the default version
    setting manually using this method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1namesetdefault-post-openapi.md
- name: Google Cloud Machine Learning Engine - Delete Model Version
  x-api-slug: v1name-delete
  description: |-
    Deletes a model version.

    Each model can have multiple versions deployed and in use at any given
    time. Use this method to remove a single version.

    Note: You cannot delete the version that is set as the default version
    of the model unless it is the only remaining version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1name-delete-openapi.md
- name: Google Cloud Machine Learning Engine - Delete Model Version
  x-api-slug: v1name-delete
  description: |-
    Deletes a model version.

    Each model can have multiple versions deployed and in use at any given
    time. Use this method to remove a single version.

    Note: You cannot delete the version that is set as the default version
    of the model unless it is the only remaining version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1name-delete-openapi.md
- name: Google Cloud Machine Learning Engine - Get Model Version
  x-api-slug: v1name-get
  description: |-
    Gets information about a model version.

    Models can have multiple versions. You can call
    [projects.models.versions.list](/ml/reference/rest/v1/projects.models.versions/list)
    to get the same information that this method returns for all of the
    versions of a model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1name-get-openapi.md
- name: Google Cloud Machine Learning Engine - Delete Model Version
  x-api-slug: v1name-delete
  description: |-
    Deletes a model version.

    Each model can have multiple versions deployed and in use at any given
    time. Use this method to remove a single version.

    Note: You cannot delete the version that is set as the default version
    of the model unless it is the only remaining version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/versions/master/_listings/google-cloud-machine-learning-engine/v1name-delete-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.cloud.key.management.service.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.cloud.machine.learning.engine.stack.network
- type: x-change-log
  url: https://cloud.google.com/ml-engine/docs/resources/release-notes
- type: x-command-line-interface
  url: https://cloud.google.com/sdk/gcloud/reference/ml-engine/
- type: x-concepts
  url: https://cloud.google.com/ml-engine/docs/concepts/
- type: x-documentation
  url: https://cloud.google.com/ml-engine/docs/
- type: x-getting-started
  url: https://cloud.google.com/ml-engine/docs/quickstarts/
- type: x-pricing
  url: https://cloud.google.com/ml-engine/pricing
- type: x-rate-limits
  url: https://cloud.google.com/ml-engine/quotas
- type: x-service-level-agreements
  url: https://cloud.google.com/ml-engine/sla
- type: x-support
  url: https://cloud.google.com/ml-engine/docs/resources/support
- type: x-terms-of-service
  url: https://cloud.google.com/terms/
- type: x-tutorials
  url: https://cloud.google.com/ml-engine/docs/tutorials/
- type: x-versioning
  url: https://cloud.google.com/ml-engine/docs/concepts/versioning
- type: x-website
  url: https://cloud.google.com/ml-engine/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---