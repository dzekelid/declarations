---
swagger: "2.0"
x-collection-name: AXA Assistance
x-complete: 1
info:
  title: AXA Assistance
  description: axa-assistance-is-a-worldwide-specialist-for-car-insurance-travel-health-and-home-services--trust-in-axa-assistance-for-your-insurance
  version: 1.0.0
host: sandbox.api.axa-assistance.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /assistance/v1/home/glaziery_damage/declarations/{declaration_id}/policy_holders:
    get:
      summary: Gets the information linked to the policy holder of the glaziery damage
        declaration
      description: Gets the information linked to the policy holder of the glaziery
        damage declaration
      operationId: getAssistanceV1HomeGlaziery_damageDeclarationsDeclaration_idPolicy_holders
      x-api-path-slug: assistancev1homeglaziery-damagedeclarationsdeclaration-idpolicy-holders-get
      parameters:
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - information
      - linked
      - to
      - the
      - policy
      - holder
      - of
      - the
      - glaziery
      - damage
      - Declarations
  /assistance/v1/home/home_appliance_damage/declarations/{declaration_id}/policy_holders:
    get:
      summary: Gets the information linked to the policy holder of the home appliance
        damage declaration
      description: Gets the information linked to the policy holder of the home appliance
        damage declaration
      operationId: getAssistanceV1HomeHome_appliance_damageDeclarationsDeclaration_idPolicy_holders
      x-api-path-slug: assistancev1homehome-appliance-damagedeclarationsdeclaration-idpolicy-holders-get
      parameters:
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - information
      - linked
      - to
      - the
      - policy
      - holder
      - of
      - the
      - home
      - appliance
      - damage
      - Declarations
  /assistance/v1/home/locksmithing_damage/declarations/{declaration_id}/policy_holders:
    get:
      summary: Gets the information linked to the policy holder of the locksmithing
        damage declaration
      description: Gets the information linked to the policy holder of the locksmithing
        damage declaration
      operationId: getAssistanceV1HomeLocksmithing_damageDeclarationsDeclaration_idPolicy_holders
      x-api-path-slug: assistancev1homelocksmithing-damagedeclarationsdeclaration-idpolicy-holders-get
      parameters:
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - information
      - linked
      - to
      - the
      - policy
      - holder
      - of
      - the
      - locksmithing
      - damage
      - Declarations
  /assistance/v1/home/water_damage/declarations/{declaration_id}/policy_holders:
    get:
      summary: Gets the information related to each the policy holder of the water
        damage declaration
      description: Gets the information related to each the policy holder of the water
        damage declaration
      operationId: getAssistanceV1HomeWater_damageDeclarationsDeclaration_idPolicy_holders
      x-api-path-slug: assistancev1homewater-damagedeclarationsdeclaration-idpolicy-holders-get
      parameters:
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - information
      - related
      - to
      - each
      - the
      - policy
      - holder
      - of
      - the
      - water
      - damage
      - Declarations
  /assistance/v1/home/electric_damage/declarations/{declaration_id}/confirm:
    post:
      summary: Electric declaration confirmation
      description: Electric declaration confirmation
      operationId: postAssistanceV1HomeElectric_damageDeclarationsDeclaration_idConfirm
      x-api-path-slug: assistancev1homeelectric-damagedeclarationsdeclaration-idconfirm-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Electric
      - Declarations
      - confirmation
  /assistance/v1/home/electric_damage/declarations/{declaration_id}/contacts:
    post:
      summary: Adds contact information of the electric damage declaration
      description: Adds contact information of the electric damage declaration
      operationId: postAssistanceV1HomeElectric_damageDeclarationsDeclaration_idContacts
      x-api-path-slug: assistancev1homeelectric-damagedeclarationsdeclaration-idcontacts-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - contact
      - information
      - of
      - the
      - electric
      - damage
      - Declarations
  /assistance/v1/home/electric_damage/declarations/{declaration_id}/close:
    post:
      summary: Electric declaration closure
      description: Electric declaration closure
      operationId: postAssistanceV1HomeElectric_damageDeclarationsDeclaration_idClose
      x-api-path-slug: assistancev1homeelectric-damagedeclarationsdeclaration-idclose-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Electric
      - Declarations
      - closure
  /assistance/v1/home/gas_damage/declarations/{declaration_id}/contacts:
    post:
      summary: Adds contact information of the gas damage declaration
      description: Adds contact information of the gas damage declaration
      operationId: postAssistanceV1HomeGas_damageDeclarationsDeclaration_idContacts
      x-api-path-slug: assistancev1homegas-damagedeclarationsdeclaration-idcontacts-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - contact
      - information
      - of
      - the
      - gaAssistance
      - damage
      - Declarations
  /assistance/v1/home/gas_damage/declarations/{declaration_id}/confirm:
    post:
      summary: Gas declaration confirmation
      description: Gas declaration confirmation
      operationId: postAssistanceV1HomeGas_damageDeclarationsDeclaration_idConfirm
      x-api-path-slug: assistancev1homegas-damagedeclarationsdeclaration-idconfirm-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - Declarations
      - confirmation
  /assistance/v1/home/gas_damage/declarations/{declaration_id}/close:
    post:
      summary: Gas declaration closure
      description: Gas declaration closure
      operationId: postAssistanceV1HomeGas_damageDeclarationsDeclaration_idClose
      x-api-path-slug: assistancev1homegas-damagedeclarationsdeclaration-idclose-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - Declarations
      - closure
  /assistance/v1/home/glaziery_damage/declarations/{declaration_id}/close:
    post:
      summary: Closes the declaration after an other fixing solution
      description: Closes the declaration after an other fixing solution
      operationId: postAssistanceV1HomeGlaziery_damageDeclarationsDeclaration_idClose
      x-api-path-slug: assistancev1homeglaziery-damagedeclarationsdeclaration-idclose-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - CloseAssistance
      - the
      - Declarations
      - afterother
      - fixing
      - solution
  /assistance/v1/home/glaziery_damage/declarations/{declaration_id}/contacts:
    post:
      summary: Adds contact information of the glaziery damage declaration
      description: Adds contact information of the glaziery damage declaration
      operationId: postAssistanceV1HomeGlaziery_damageDeclarationsDeclaration_idContacts
      x-api-path-slug: assistancev1homeglaziery-damagedeclarationsdeclaration-idcontacts-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - contact
      - information
      - of
      - the
      - glaziery
      - damage
      - Declarations
  /assistance/v1/home/home_appliance_damage/declarations/{declaration_id}/contacts:
    post:
      summary: Adds contact information of the home appliance damage declaration
      description: Adds contact information of the home appliance damage declaration
      operationId: postAssistanceV1HomeHome_appliance_damageDeclarationsDeclaration_idContacts
      x-api-path-slug: assistancev1homehome-appliance-damagedeclarationsdeclaration-idcontacts-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - contact
      - information
      - of
      - the
      - home
      - appliance
      - damage
      - Declarations
  /assistance/v1/home/home_appliance_damage/declarations/{declaration_id}/close:
    post:
      summary: Closes the declaration after an other fixing solution
      description: Closes the declaration after an other fixing solution
      operationId: postAssistanceV1HomeHome_appliance_damageDeclarationsDeclaration_idClose
      x-api-path-slug: assistancev1homehome-appliance-damagedeclarationsdeclaration-idclose-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the request
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - CloseAssistance
      - the
      - Declarations
      - afterother
      - fixing
      - solution
  /assistance/v1/home/locksmithing_damage/declarations/{declaration_id}/close:
    post:
      summary: Closes the declaration after an other fixing solution
      description: Closes the declaration after an other fixing solution
      operationId: postAssistanceV1HomeLocksmithing_damageDeclarationsDeclaration_idClose
      x-api-path-slug: assistancev1homelocksmithing-damagedeclarationsdeclaration-idclose-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - CloseAssistance
      - the
      - Declarations
      - afterother
      - fixing
      - solution
  /assistance/v1/home/locksmithing_damage/declarations/{declaration_id}/contacts:
    post:
      summary: Adds contact information of the locksmithing damage declaration
      description: Adds contact information of the locksmithing damage declaration
      operationId: postAssistanceV1HomeLocksmithing_damageDeclarationsDeclaration_idContacts
      x-api-path-slug: assistancev1homelocksmithing-damagedeclarationsdeclaration-idcontacts-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - contact
      - information
      - of
      - the
      - locksmithing
      - damage
      - Declarations
  /assistance/v1/home/water_damage/declarations/{declaration_id}/contacts:
    post:
      summary: Adds contact information of the water damage declaration
      description: Adds contact information of the water damage declaration
      operationId: postAssistanceV1HomeWater_damageDeclarationsDeclaration_idContacts
      x-api-path-slug: assistancev1homewater-damagedeclarationsdeclaration-idcontacts-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - contact
      - information
      - of
      - the
      - water
      - damage
      - Declarations
  /assistance/v1/home/water_damage/declarations/{declaration_id}/close:
    post:
      summary: Closes the declaration after an other fixing solution
      description: Closes the declaration after an other fixing solution
      operationId: postAssistanceV1HomeWater_damageDeclarationsDeclaration_idClose
      x-api-path-slug: assistancev1homewater-damagedeclarationsdeclaration-idclose-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - CloseAssistance
      - the
      - Declarations
      - afterother
      - fixing
      - solution
  /assistance/v1/home/electric_damage/declarations/{declaration_id}:
    patch:
      summary: Updates information related to the electric damage declaration
      description: Updates information related to the electric damage declaration
      operationId: patchAssistanceV1HomeElectric_damageDeclarationsDeclaration_id
      x-api-path-slug: assistancev1homeelectric-damagedeclarationsdeclaration-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - information
      - related
      - to
      - the
      - electric
      - damage
      - Declarations
  /assistance/v1/home/gas_damage/declarations/{declaration_id}:
    patch:
      summary: Updates information related to the gas damage declaration
      description: Updates information related to the gas damage declaration
      operationId: patchAssistanceV1HomeGas_damageDeclarationsDeclaration_id
      x-api-path-slug: assistancev1homegas-damagedeclarationsdeclaration-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - information
      - related
      - to
      - the
      - gaAssistance
      - damage
      - Declarations
  /assistance/v1/home/glaziery_damage/declarations/{declaration_id}:
    patch:
      summary: Updates information related to the glaziery damage declaration
      description: Updates information related to the glaziery damage declaration
      operationId: patchAssistanceV1HomeGlaziery_damageDeclarationsDeclaration_id
      x-api-path-slug: assistancev1homeglaziery-damagedeclarationsdeclaration-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - information
      - related
      - to
      - the
      - glaziery
      - damage
      - Declarations
  /assistance/v1/home/home_appliance_damage/declarations/{declaration_id}:
    patch:
      summary: Updates information related to the home appliance damage declaration
      description: Updates information related to the home appliance damage declaration
      operationId: patchAssistanceV1HomeHome_appliance_damageDeclarationsDeclaration_id
      x-api-path-slug: assistancev1homehome-appliance-damagedeclarationsdeclaration-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - information
      - related
      - to
      - the
      - home
      - appliance
      - damage
      - Declarations
  /assistance/v1/home/locksmithing_damage/declarations/{declaration_id}:
    patch:
      summary: Updates information related to the locksmithing damage declaration
      description: Updates information related to the locksmithing damage declaration
      operationId: patchAssistanceV1HomeLocksmithing_damageDeclarationsDeclaration_id
      x-api-path-slug: assistancev1homelocksmithing-damagedeclarationsdeclaration-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - information
      - related
      - to
      - the
      - locksmithing
      - damage
      - Declarations
  /assistance/v1/home/water_damage/declarations/{declaration_id}:
    patch:
      summary: Updates information related to the water damage declaration
      description: Updates information related to the water damage declaration
      operationId: patchAssistanceV1HomeWater_damageDeclarationsDeclaration_id
      x-api-path-slug: assistancev1homewater-damagedeclarationsdeclaration-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - information
      - related
      - to
      - the
      - water
      - damage
      - Declarations
  /assistance/v1/home/electric_damage/declarations/{declaration_id}/policy_holders/{policy_holder_id}:
    patch:
      summary: Updates the policy holder information of the electric damage declaration
      description: Updates the policy holder information of the electric damage declaration
      operationId: patchAssistanceV1HomeElectric_damageDeclarationsDeclaration_idPolicy_holdersPolicy_holder_id
      x-api-path-slug: assistancev1homeelectric-damagedeclarationsdeclaration-idpolicy-holderspolicy-holder-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      - in: path
        name: policy_holder_id
        description: ID of the policy holder
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - policy
      - holder
      - information
      - of
      - the
      - electric
      - damage
      - Declarations
  /assistance/v1/home/gas_damage/declarations/{declaration_id}/policy_holders/{policy_holder_id}:
    patch:
      summary: Updates the policy holder information of the gas damage declaration
      description: Updates the policy holder information of the gas damage declaration
      operationId: patchAssistanceV1HomeGas_damageDeclarationsDeclaration_idPolicy_holdersPolicy_holder_id
      x-api-path-slug: assistancev1homegas-damagedeclarationsdeclaration-idpolicy-holderspolicy-holder-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      - in: path
        name: policy_holder_id
        description: ID of the policy holder
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - policy
      - holder
      - information
      - of
      - the
      - gaAssistance
      - damage
      - Declarations
  /assistance/v1/home/glaziery_damage/declarations/{declaration_id}/policy_holders/{policy_holder_id}:
    patch:
      summary: Updates the policy holder information of the glaziery damage declaration
      description: Updates the policy holder information of the glaziery damage declaration
      operationId: patchAssistanceV1HomeGlaziery_damageDeclarationsDeclaration_idPolicy_holdersPolicy_holder_id
      x-api-path-slug: assistancev1homeglaziery-damagedeclarationsdeclaration-idpolicy-holderspolicy-holder-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      - in: path
        name: policy_holder_id
        description: ID of the policy holder
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - policy
      - holder
      - information
      - of
      - the
      - glaziery
      - damage
      - Declarations
  /assistance/v1/home/home_appliance_damage/declarations/{declaration_id}/policy_holders/{policy_holder_id}:
    patch:
      summary: Update the policy holder information of the home appliance damage declaration
      description: Update the policy holder information of the home appliance damage
        declaration
      operationId: patchAssistanceV1HomeHome_appliance_damageDeclarationsDeclaration_idPolicy_holdersPolicy_holder_id
      x-api-path-slug: assistancev1homehome-appliance-damagedeclarationsdeclaration-idpolicy-holderspolicy-holder-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      - in: path
        name: policy_holder_id
        description: ID of the policy holder
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - the
      - policy
      - holder
      - information
      - of
      - the
      - home
      - appliance
      - damage
      - Declarations
  /assistance/v1/home/locksmithing_damage/declarations/{declaration_id}/policy_holders/{policy_holder_id}:
    patch:
      summary: Updates the policy holder information of the locksmithing damage declaration
      description: Updates the policy holder information of the locksmithing damage
        declaration
      operationId: patchAssistanceV1HomeLocksmithing_damageDeclarationsDeclaration_idPolicy_holdersPolicy_holder_id
      x-api-path-slug: assistancev1homelocksmithing-damagedeclarationsdeclaration-idpolicy-holderspolicy-holder-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      - in: path
        name: policy_holder_id
        description: ID of the policy holder
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - policy
      - holder
      - information
      - of
      - the
      - locksmithing
      - damage
      - Declarations
  /assistance/v1/home/water_damage/declarations/{declaration_id}/policy_holders/{policy_holder_id}:
    patch:
      summary: Updates the policy holder information of the water damage declaration
      description: Updates the policy holder information of the water damage declaration
      operationId: patchAssistanceV1HomeWater_damageDeclarationsDeclaration_idPolicy_holdersPolicy_holder_id
      x-api-path-slug: assistancev1homewater-damagedeclarationsdeclaration-idpolicy-holderspolicy-holder-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      - in: path
        name: policy_holder_id
        description: ID of the policy holder
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - policy
      - holder
      - information
      - of
      - the
      - water
      - damage
      - Declarations
---