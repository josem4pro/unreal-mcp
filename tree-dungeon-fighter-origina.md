.
├── asset_summary_for_claude_code.md
├── asset_swarm_dungeon.py
├── asset_swarm.py
├── check_refactor_status.py
├── Config
│   ├── DefaultEditor.ini
│   ├── DefaultEngine.ini
│   ├── DefaultGame.ini
│   ├── DefaultGameplayTags.ini
│   ├── DefaultInput.ini
│   └── Layouts
├── Content
│   ├── Characters
│   │   ├── Enemies
│   │   │   ├── EnemyBase
│   │   │   │   ├── Assets
│   │   │   │   │   ├── Drops
│   │   │   │   │   │   ├── Asset
│   │   │   │   │   │   │   ├── Material
│   │   │   │   │   │   │   │   ├── MIM_Props.uasset
│   │   │   │   │   │   │   │   └── MI_Skeleton_01a.uasset
│   │   │   │   │   │   │   ├── Mesh
│   │   │   │   │   │   │   │   └── Props
│   │   │   │   │   │   │   │       └── SM_Skull_01a.uasset
│   │   │   │   │   │   │   └── Texture
│   │   │   │   │   │   │       └── T_Skeleton
│   │   │   │   │   │   │           ├── T_Skeleton_01a_D.uasset
│   │   │   │   │   │   │           ├── T_Skeleton_01a_N.uasset
│   │   │   │   │   │   │           └── T_Skeleton_01a_ORM.uasset
│   │   │   │   │   │   └── MasterMaterial
│   │   │   │   │   │       ├── Material
│   │   │   │   │   │       │   └── MM_MaterMaterial.uasset
│   │   │   │   │   │       ├── Material_Function
│   │   │   │   │   │       │   ├── MF_AODirt.uasset
│   │   │   │   │   │       │   ├── MF_FourNormalCombine.uasset
│   │   │   │   │   │       │   ├── MF_FuzzyMasterlayer.uasset
│   │   │   │   │   │       │   ├── MF_HeightExtracted.uasset
│   │   │   │   │   │       │   ├── MF_MacroAlbedo.uasset
│   │   │   │   │   │       │   ├── MF_MacroNormal.uasset
│   │   │   │   │   │       │   ├── MF_Masterlayer.uasset
│   │   │   │   │   │       │   ├── MF_MatLayerBlend.uasset
│   │   │   │   │   │       │   ├── MF_RippleS.uasset
│   │   │   │   │   │       │   ├── MF_Ripple.uasset
│   │   │   │   │   │       │   ├── MF_ScaleBaseTile.uasset
│   │   │   │   │   │       │   ├── MF_Upvector.uasset
│   │   │   │   │   │       │   ├── MF_Vertexpaint.uasset
│   │   │   │   │   │       │   ├── MF_Wetness.uasset
│   │   │   │   │   │       │   └── MF_WorldAlignedNormal.uasset
│   │   │   │   │   │       └── Texture
│   │   │   │   │   │           ├── T_Grunge
│   │   │   │   │   │           │   ├── T_Grunge_02a.uasset
│   │   │   │   │   │           │   └── T_Grunge_03a.uasset
│   │   │   │   │   │           ├── T_Height_H.uasset
│   │   │   │   │   │           ├── T_Mask_ORM.uasset
│   │   │   │   │   │           ├── T_rain_ripples.uasset
│   │   │   │   │   │           ├── T_TintMask_01_TM.uasset
│   │   │   │   │   │           ├── T_TintMask_02_TM.uasset
│   │   │   │   │   │           └── T_Water_N.uasset
│   │   │   │   │   └── Skeleton
│   │   │   │   │       ├── AnImations
│   │   │   │   │       │   ├── AM_Hip_Hop_Dancing_MontageF.uasset
│   │   │   │   │       │   ├── AM_Hip_Hop_Dancing_Montage.uasset
│   │   │   │   │       │   ├── AM_RightHook.uasset
│   │   │   │   │       │   ├── AS_Flair.uasset
│   │   │   │   │       │   ├── AS_Hip_Hop_Dancing.uasset
│   │   │   │   │       │   ├── AS_Moonwalk.uasset
│   │   │   │   │       │   ├── AS_Right_HOOk.uasset
│   │   │   │   │       │   ├── AS_SK_Idle.uasset
│   │   │   │   │       │   ├── AS_SK_RUN.uasset
│   │   │   │   │       │   └── AS_SK_Walk.uasset
│   │   │   │   │       ├── materials
│   │   │   │   │       │   ├── MF
│   │   │   │   │       │   │   └── MF_skeleton.uasset
│   │   │   │   │       │   ├── MI_Skeleton_Inst.uasset
│   │   │   │   │       │   └── M_Skeleton.uasset
│   │   │   │   │       ├── mesh
│   │   │   │   │       │   ├── IK_Skeleton_base.uasset
│   │   │   │   │       │   ├── SK_Skeleton_base_Physics.uasset
│   │   │   │   │       │   ├── SK_Skeleton_base_Skeleton.uasset
│   │   │   │   │       │   └── SK_Skeleton_base.uasset
│   │   │   │   │       └── textures
│   │   │   │   │           ├── T_curva_dirt_dirt2.uasset
│   │   │   │   │           ├── T_skeleton_BaseColor.uasset
│   │   │   │   │           ├── T_skeleton_Emissive.uasset
│   │   │   │   │           ├── T_skeleton_Normal.uasset
│   │   │   │   │           └── T_skeleton_OcclusionRoughnessMetallic.uasset
│   │   │   │   └── Blueprints
│   │   │   │       ├── ABP_BaseEnemy.uasset
│   │   │   │       ├── BP_BaseEnemyDrop1.uasset
│   │   │   │       ├── BP_BaseEnemyDrop.uasset
│   │   │   │       ├── BP_BaseEnemyTurorial.uasset
│   │   │   │       ├── BP_BaseEnemy.uasset
│   │   │   │       └── CR_BaseEnemyRIG.uasset
│   │   │   ├── EnemyBoss
│   │   │   │   ├── Assets
│   │   │   │   │   ├── FX
│   │   │   │   │   │   ├── MI_BasicEnemy.uasset
│   │   │   │   │   │   ├── MI_Overlay.uasset
│   │   │   │   │   │   ├── M_OverlayTest.uasset
│   │   │   │   │   │   ├── T_Caustics2.uasset
│   │   │   │   │   │   ├── T_TiledFire.uasset
│   │   │   │   │   │   └── VFX
│   │   │   │   │   │       └── MagicalExplosionsVFX
│   │   │   │   │   │           ├── Essentials
│   │   │   │   │   │           │   ├── Materials
│   │   │   │   │   │           │   │   ├── M_CircleHard.uasset
│   │   │   │   │   │           │   │   ├── M_Flames.uasset
│   │   │   │   │   │           │   │   └── M_MasterSpriteMat.uasset
│   │   │   │   │   │           │   └── Textures
│   │   │   │   │   │           │       ├── T_CircleHard.uasset
│   │   │   │   │   │           │       └── T_TilingNoise.uasset
│   │   │   │   │   │           └── VFX
│   │   │   │   │   │               ├── ChaosExplosion
│   │   │   │   │   │               │   └── Materials
│   │   │   │   │   │               │       ├── MI_ChaosExplosionBeam.uasset
│   │   │   │   │   │               │       ├── MI_ChaosExplosionCircle.uasset
│   │   │   │   │   │               │       ├── MI_ChaosExplosionFlames.uasset
│   │   │   │   │   │               │       ├── MI_ChaosExplosionGlow.uasset
│   │   │   │   │   │               │       └── MI_ChaosExplosionParticles.uasset
│   │   │   │   │   │               ├── FlameBlast
│   │   │   │   │   │               │   └── Materials
│   │   │   │   │   │               │       ├── MI_FlameBlastFlames.uasset
│   │   │   │   │   │               │       └── MI_FlameBlastParticles.uasset
│   │   │   │   │   │               ├── Materials
│   │   │   │   │   │               │   ├── M_Meteor_Inst.uasset
│   │   │   │   │   │               │   └── M_Meteor.uasset
│   │   │   │   │   │               ├── Mesh
│   │   │   │   │   │               │   └── SM_Meteor.uasset
│   │   │   │   │   │               ├── N_ChaosExplosionCharged.uasset
│   │   │   │   │   │               ├── N_FlameBlastCharged.uasset
│   │   │   │   │   │               ├── N_Meteor.uasset
│   │   │   │   │   │               └── Textures
│   │   │   │   │   │                   ├── T_Gradient.uasset
│   │   │   │   │   │                   ├── T_RockNormal.uasset
│   │   │   │   │   │                   ├── T_TiledFire.uasset
│   │   │   │   │   │                   └── T_TilingNoise.uasset
│   │   │   │   │   ├── Global
│   │   │   │   │   │   ├── Eyes
│   │   │   │   │   │   │   ├── MaterialFunctions
│   │   │   │   │   │   │   │   └── ML_EyeRefraction.uasset
│   │   │   │   │   │   │   ├── Materials
│   │   │   │   │   │   │   │   ├── M_Eye_Occlusion.uasset
│   │   │   │   │   │   │   │   ├── M_EyeRefractive.uasset
│   │   │   │   │   │   │   │   ├── ML_TacticiaULTEye.uasset
│   │   │   │   │   │   │   │   ├── M_TearDuct_2.uasset
│   │   │   │   │   │   │   │   └── M_TearLine.uasset
│   │   │   │   │   │   │   └── Textures
│   │   │   │   │   │   │       ├── EyeInner_Profile.uasset
│   │   │   │   │   │   │       ├── T_DecalMask_Radial03.uasset
│   │   │   │   │   │   │       ├── TearDuctSubsurfaceProfile.uasset
│   │   │   │   │   │   │       ├── T_EyeIrisBaseColor_Example_2.uasset
│   │   │   │   │   │   │       ├── T_EyeMidPlaneDisplacement_Example.uasset
│   │   │   │   │   │   │       ├── T_EYE_NORMALS.uasset
│   │   │   │   │   │   │       ├── T_EyeOcclusion2.uasset
│   │   │   │   │   │   │       ├── T_EyeScleraBaseColor_Example_2.uasset
│   │   │   │   │   │   │       ├── T_Eye_Tearduct__normals2.uasset
│   │   │   │   │   │   │       ├── T_Eye_Wet_Normal.uasset
│   │   │   │   │   │   │       ├── T_Sphere_EYE_NORMALS.uasset
│   │   │   │   │   │   │       └── T_Swirly_Noise.uasset
│   │   │   │   │   │   ├── MaterialFunctions
│   │   │   │   │   │   │   ├── HitFlash.uasset
│   │   │   │   │   │   │   ├── MaterialLayerConstructors
│   │   │   │   │   │   │   │   ├── MF_BaseColorTintAndContrast.uasset
│   │   │   │   │   │   │   │   ├── MF_RoughnessAdjustment.uasset
│   │   │   │   │   │   │   │   ├── MLC_ScratchAndGrime.uasset
│   │   │   │   │   │   │   │   └── MLC_Standard.uasset
│   │   │   │   │   │   │   ├── MF_BrightnessAdjust.uasset
│   │   │   │   │   │   │   ├── MF_CharacterEffects.uasset
│   │   │   │   │   │   │   ├── MF_CharacterGradient.uasset
│   │   │   │   │   │   │   ├── MF_DeathFade.uasset
│   │   │   │   │   │   │   ├── MF_OrionCharacterAO.uasset
│   │   │   │   │   │   │   ├── MF_OrionRimlight.uasset
│   │   │   │   │   │   │   └── MF_RimLight.uasset
│   │   │   │   │   │   ├── MaterialLayers
│   │   │   │   │   │   │   ├── Fabric
│   │   │   │   │   │   │   │   ├── ML_MutedGreenCloth02.uasset
│   │   │   │   │   │   │   │   ├── T_FineFabric01_N.uasset
│   │   │   │   │   │   │   │   └── T_FineFabric01.uasset
│   │   │   │   │   │   │   ├── Leather
│   │   │   │   │   │   │   │   ├── ML_ThinLeather01_Brown.uasset
│   │   │   │   │   │   │   │   ├── T_ML_FineLeather01_Brown.uasset
│   │   │   │   │   │   │   │   └── T_ML_FineLeather01_N.uasset
│   │   │   │   │   │   │   ├── Metal
│   │   │   │   │   │   │   │   ├── ML_blue_Metal.uasset
│   │   │   │   │   │   │   │   ├── ML_Rust01.uasset
│   │   │   │   │   │   │   │   ├── ML_Scratched_metal.uasset
│   │   │   │   │   │   │   │   ├── T_Blue_Metal02.uasset
│   │   │   │   │   │   │   │   ├── T_Kurohane_Metal_Tiling_D.uasset
│   │   │   │   │   │   │   │   ├── T_Rust01_N.uasset
│   │   │   │   │   │   │   │   └── T_Rust01.uasset
│   │   │   │   │   │   │   ├── ML_Blank.uasset
│   │   │   │   │   │   │   ├── Rock
│   │   │   │   │   │   │   │   ├── MF_LavaColorTint.uasset
│   │   │   │   │   │   │   │   ├── MF_Slate.uasset
│   │   │   │   │   │   │   │   ├── T_Rampage_V001_RockDetail_D.uasset
│   │   │   │   │   │   │   │   ├── T_Rampage_V001_RockDetail_M.uasset
│   │   │   │   │   │   │   │   ├── T_RockTextureTile_000_N.uasset
│   │   │   │   │   │   │   │   ├── T_SlateTextureTile_000_D.uasset
│   │   │   │   │   │   │   │   ├── T_SlateTextureTile_000_N.uasset
│   │   │   │   │   │   │   │   └── T_Weathered__Detail001_Mask.uasset
│   │   │   │   │   │   │   ├── Rubber
│   │   │   │   │   │   │   │   └── T_Blank_N.uasset
│   │   │   │   │   │   │   └── Skin
│   │   │   │   │   │   │       ├── T_Pore_Normals2.uasset
│   │   │   │   │   │   │       ├── T_Pore_Specular.uasset
│   │   │   │   │   │   │       └── T_Tiling_Circuit.uasset
│   │   │   │   │   │   ├── Mouth
│   │   │   │   │   │   │   └── Materials
│   │   │   │   │   │   │       └── TeethSubsurfaceProfile.uasset
│   │   │   │   │   │   ├── ParameterCollections
│   │   │   │   │   │   │   └── OrionGlobalGameplayCollection.uasset
│   │   │   │   │   │   ├── T_Black_Linear.uasset
│   │   │   │   │   │   ├── Textures
│   │   │   │   │   │   │   ├── EpicQuadPanorama_CC.uasset
│   │   │   │   │   │   │   ├── Flares
│   │   │   │   │   │   │   │   └── T_Muriel_Corona_D.uasset
│   │   │   │   │   │   │   ├── Masks
│   │   │   │   │   │   │   │   ├── T_DebrisConeMask.uasset
│   │   │   │   │   │   │   │   └── T_SplineThickness_Mask.uasset
│   │   │   │   │   │   │   ├── Noise
│   │   │   │   │   │   │   │   ├── T_AtmosphericCloudNoise01_N.uasset
│   │   │   │   │   │   │   │   ├── T_AtmosphericCloudNoise01.uasset
│   │   │   │   │   │   │   │   └── T_AtmosphericCloudNoise03.uasset
│   │   │   │   │   │   │   ├── Tile
│   │   │   │   │   │   │   │   └── Noise
│   │   │   │   │   │   │   │       └── T_SmokeTile_N.uasset
│   │   │   │   │   │   │   └── Water
│   │   │   │   │   │   │       └── T_WaterFlow_01_Foam_Tiled.uasset
│   │   │   │   │   │   └── T_TestML_Mask.uasset
│   │   │   │   │   └── Heroes
│   │   │   │   │       └── Rampage
│   │   │   │   │           ├── Animations
│   │   │   │   │           │   ├── Ability_Energize_FinsDown.uasset
│   │   │   │   │           │   ├── Ability_Energize_FinsUpLoop.uasset
│   │   │   │   │           │   ├── Ability_Energize.uasset
│   │   │   │   │           │   ├── Ability_Enrage_End.uasset
│   │   │   │   │           │   ├── Ability_Enrage_Start.uasset
│   │   │   │   │           │   ├── Ability_GroundSmash_End.uasset
│   │   │   │   │           │   ├── Ability_GroundSmash_Loop.uasset
│   │   │   │   │           │   ├── Ability_GroundSmash_Start.uasset
│   │   │   │   │           │   ├── Ability_RipNToss_Cancel.uasset
│   │   │   │   │           │   ├── Ability_RipNToss_Idle.uasset
│   │   │   │   │           │   ├── Ability_RipNToss_Jog_Bwd.uasset
│   │   │   │   │           │   ├── Ability_RipNToss_Jog_Fwd.uasset
│   │   │   │   │           │   ├── Ability_RipNToss_Jog_Lft.uasset
│   │   │   │   │           │   ├── Ability_RipNToss_Jog_Rgt.uasset
│   │   │   │   │           │   ├── Ability_RipNToss_Rip.uasset
│   │   │   │   │           │   ├── Ability_RipNToss_Toss_Enraged.uasset
│   │   │   │   │           │   ├── Ability_RipNToss_Toss.uasset
│   │   │   │   │           │   ├── Ability_RMB_Smash_InAir.uasset
│   │   │   │   │           │   ├── Ability_RMB_Smash.uasset
│   │   │   │   │           │   ├── AM_BossAttack1.uasset
│   │   │   │   │           │   ├── AM_BossAttack2.uasset
│   │   │   │   │           │   ├── AM_BossAttack3.uasset
│   │   │   │   │           │   ├── AM_BossAttack4.uasset
│   │   │   │   │           │   ├── AM_BossDance.uasset
│   │   │   │   │           │   ├── AM_Destruction.uasset
│   │   │   │   │           │   ├── AM_DistanceAttack.uasset
│   │   │   │   │           │   ├── AM_Enrage.uasset
│   │   │   │   │           │   ├── AM_RockPick.uasset
│   │   │   │   │           │   ├── AM_ThrowBigMeteor.uasset
│   │   │   │   │           │   ├── AM_ThrowMeteor.uasset
│   │   │   │   │           │   ├── AM_ThrowRock.uasset
│   │   │   │   │           │   ├── AS_FlyAnim.uasset
│   │   │   │   │           │   ├── AS_GetRock.uasset
│   │   │   │   │           │   ├── AS_HitGround.uasset
│   │   │   │   │           │   ├── AS_JumpIdle.uasset
│   │   │   │   │           │   ├── AS_LandJump.uasset
│   │   │   │   │           │   ├── AS_MeleeAttack1.uasset
│   │   │   │   │           │   ├── AS_MeleeAttack2.uasset
│   │   │   │   │           │   ├── AS_MeleeAttack3.uasset
│   │   │   │   │           │   ├── AS_ROAR.uasset
│   │   │   │   │           │   ├── AS_ROARv2.uasset
│   │   │   │   │           │   ├── AS_ROCKTHROUGHT.uasset
│   │   │   │   │           │   ├── AS_Standing_1H_Magic_Attack_03.uasset
│   │   │   │   │           │   ├── AS_Standing_2H_Magic_Area_Attack_01.uasset
│   │   │   │   │           │   ├── AS_Wide_Arm_Spell_Casting.uasset
│   │   │   │   │           │   ├── Attack_Biped_Melee_A_Montage.uasset
│   │   │   │   │           │   ├── Attack_Biped_Melee_A.uasset
│   │   │   │   │           │   ├── Attack_Biped_Melee_B_Montage.uasset
│   │   │   │   │           │   ├── Attack_Biped_Melee_B.uasset
│   │   │   │   │           │   ├── Attack_Biped_Melee_C_Montage.uasset
│   │   │   │   │           │   ├── Attack_Biped_Melee_C.uasset
│   │   │   │   │           │   ├── Attack_Melee_A.uasset
│   │   │   │   │           │   ├── Attack_Melee_B.uasset
│   │   │   │   │           │   ├── Attack_Melee_C.uasset
│   │   │   │   │           │   ├── Blendspaces
│   │   │   │   │           │   │   ├── JogBwdSlopeLean_Quad.uasset
│   │   │   │   │           │   │   ├── JogFwdSlopeLean_Quad.uasset
│   │   │   │   │           │   │   ├── JogLeftSlopeLean_Quad.uasset
│   │   │   │   │           │   │   ├── JogRightSlopeLean_Quad.uasset
│   │   │   │   │           │   │   ├── Locomotion_Ability_RipNToss.uasset
│   │   │   │   │           │   │   ├── Locomotion_Biped.uasset
│   │   │   │   │           │   │   └── Locomotion_Quad.uasset
│   │   │   │   │           │   ├── Bound.uasset
│   │   │   │   │           │   ├── Cast.uasset
│   │   │   │   │           │   ├── Chicken_Dance.uasset
│   │   │   │   │           │   ├── Death_A.uasset
│   │   │   │   │           │   ├── Emote_Master_Roar_T3.uasset
│   │   │   │   │           │   ├── Emote_Swing_M2.uasset
│   │   │   │   │           │   ├── Emote_Taunt_ThrowDirtRoar_T1.uasset
│   │   │   │   │           │   ├── Fins_Default.uasset
│   │   │   │   │           │   ├── Fins_Spread.uasset
│   │   │   │   │           │   ├── HitReact_Back.uasset
│   │   │   │   │           │   ├── HitReact_Front.uasset
│   │   │   │   │           │   ├── HitReact_Left.uasset
│   │   │   │   │           │   ├── HitReact_Right.uasset
│   │   │   │   │           │   ├── Idle_Biped.uasset
│   │   │   │   │           │   ├── IdleBreak.uasset
│   │   │   │   │           │   ├── Idle.uasset
│   │   │   │   │           │   ├── Jog_Biped_Bwd.uasset
│   │   │   │   │           │   ├── Jog_Biped_Fwd.uasset
│   │   │   │   │           │   ├── Jog_Biped_Lft.uasset
│   │   │   │   │           │   ├── Jog_Biped_Rt.uasset
│   │   │   │   │           │   ├── Jog_Bwd_CircleLeft.uasset
│   │   │   │   │           │   ├── Jog_Bwd_CircleRight.uasset
│   │   │   │   │           │   ├── Jog_Bwd_Dowhnill.uasset
│   │   │   │   │           │   ├── Jog_Bwd_Pivot180.uasset
│   │   │   │   │           │   ├── Jog_Bwd_Start.uasset
│   │   │   │   │           │   ├── Jog_Bwd_Stop.uasset
│   │   │   │   │           │   ├── Jog_BwdToFwd_Spin_ccw.uasset
│   │   │   │   │           │   ├── Jog_BwdToFwd_Spin_cw.uasset
│   │   │   │   │           │   ├── Jog_Bwd_Uphill.uasset
│   │   │   │   │           │   ├── Jog_Fwd_CircleLeft.uasset
│   │   │   │   │           │   ├── Jog_Fwd_CircleRight.uasset
│   │   │   │   │           │   ├── Jog_Fwd_Downhill.uasset
│   │   │   │   │           │   ├── Jog_Fwd_Pivot180.uasset
│   │   │   │   │           │   ├── Jog_Fwd_Start.uasset
│   │   │   │   │           │   ├── Jog_Fwd_Stop.uasset
│   │   │   │   │           │   ├── Jog_FwdToBwd_Spin_ccw.uasset
│   │   │   │   │           │   ├── Jog_FwdToBwd_Spin_cw.uasset
│   │   │   │   │           │   ├── Jog_Fwd_Uphill.uasset
│   │   │   │   │           │   ├── Jog_Left_Pivot180.uasset
│   │   │   │   │           │   ├── Jog_Left_Start.uasset
│   │   │   │   │           │   ├── Jog_Left_Stop.uasset
│   │   │   │   │           │   ├── Jog_Left_Uphill.uasset
│   │   │   │   │           │   ├── Jog_Lft_Downhill.uasset
│   │   │   │   │           │   ├── Jog_Quad_Bwd.uasset
│   │   │   │   │           │   ├── Jog_Quad_Fwd.uasset
│   │   │   │   │           │   ├── Jog_Quad_Lft.uasset
│   │   │   │   │           │   ├── Jog_Quad_Rt.uasset
│   │   │   │   │           │   ├── Jog_Right_Pivot180.uasset
│   │   │   │   │           │   ├── Jog_Right_Start.uasset
│   │   │   │   │           │   ├── Jog_Right_Stop.uasset
│   │   │   │   │           │   ├── Jog_Right_Uphill.uasset
│   │   │   │   │           │   ├── Jog_Rt_Downhill.uasset
│   │   │   │   │           │   ├── Jump_End.uasset
│   │   │   │   │           │   ├── Jump_Fall_Additive.uasset
│   │   │   │   │           │   ├── Jump_Fall.uasset
│   │   │   │   │           │   ├── Jump_Mid.uasset
│   │   │   │   │           │   ├── Jump_Start.uasset
│   │   │   │   │           │   ├── KnockBack_Bwd.uasset
│   │   │   │   │           │   ├── KnockBack.uasset
│   │   │   │   │           │   ├── LaunchPad.uasset
│   │   │   │   │           │   ├── LevelStart_Montage.uasset
│   │   │   │   │           │   ├── LevelStart.uasset
│   │   │   │   │           │   ├── Props
│   │   │   │   │           │   │   └── Emote_SkullCracker_T3.uasset
│   │   │   │   │           │   ├── Recall.uasset
│   │   │   │   │           │   ├── Respawn.uasset
│   │   │   │   │           │   ├── Run_Fwd.uasset
│   │   │   │   │           │   ├── SelectScreen_Emote.uasset
│   │   │   │   │           │   ├── SelectScreen_Loop.uasset
│   │   │   │   │           │   ├── SelectScreen_Start.uasset
│   │   │   │   │           │   ├── SelectScreen.uasset
│   │   │   │   │           │   ├── Sprint_Biped_Bwd.uasset
│   │   │   │   │           │   ├── Sprint_Biped_Fwd.uasset
│   │   │   │   │           │   ├── Sprint_Biped_Lft.uasset
│   │   │   │   │           │   ├── Sprint_Biped_Rt.uasset
│   │   │   │   │           │   ├── Sprint_Quad_Bwd.uasset
│   │   │   │   │           │   ├── Sprint_Quad_Fwd.uasset
│   │   │   │   │           │   ├── Sprint_Quad_Lft.uasset
│   │   │   │   │           │   ├── Sprint_Quad_Rt.uasset
│   │   │   │   │           │   ├── Sprint_TravelMode_Bwd.uasset
│   │   │   │   │           │   ├── Sprint_TravelMode_Lft.uasset
│   │   │   │   │           │   ├── Sprint_TravelMode_Rgt.uasset
│   │   │   │   │           │   ├── Sprint_TravelMode.uasset
│   │   │   │   │           │   ├── Standing_Taunt_Battlecry.uasset
│   │   │   │   │           │   ├── Stun_Idle.uasset
│   │   │   │   │           │   ├── Stun_Start.uasset
│   │   │   │   │           │   ├── TravelMode_Bwd_Downhill.uasset
│   │   │   │   │           │   ├── TravelMode_Bwd_Pivot180.uasset
│   │   │   │   │           │   ├── TravelMode_Bwd_Start.uasset
│   │   │   │   │           │   ├── TravelMode_Bwd_Stop.uasset
│   │   │   │   │           │   ├── TravelMode_BwdToFwd_Spin_CCW.uasset
│   │   │   │   │           │   ├── TravelMode_BwdtoFwd_Spin_cw.uasset
│   │   │   │   │           │   ├── TravelMode_Bwd_Uphill.uasset
│   │   │   │   │           │   ├── TravelMode_Fwd_Downhill.uasset
│   │   │   │   │           │   ├── TravelMode_Fwd_Pivot180.uasset
│   │   │   │   │           │   ├── TravelMode_Fwd_Start.uasset
│   │   │   │   │           │   ├── TravelMode_Fwd_Stop.uasset
│   │   │   │   │           │   ├── TravelMode_FwdToBwd_Spin_CCW.uasset
│   │   │   │   │           │   ├── TravelMode_FwdToBwd_Spin_CW.uasset
│   │   │   │   │           │   ├── TravelMode_Fwd_Uphill.uasset
│   │   │   │   │           │   ├── Turn_Left_135_Biped.uasset
│   │   │   │   │           │   ├── Turn_Left_135_Quad.uasset
│   │   │   │   │           │   ├── Turn_Left_180_Biped.uasset
│   │   │   │   │           │   ├── Turn_Left_180_Quad.uasset
│   │   │   │   │           │   ├── Turn_Left_90_Biped.uasset
│   │   │   │   │           │   ├── Turn_Left_90_Quad.uasset
│   │   │   │   │           │   ├── Turn_Right_135_Biped.uasset
│   │   │   │   │           │   ├── Turn_Right_135_Quad.uasset
│   │   │   │   │           │   ├── Turn_Right_180_Biped.uasset
│   │   │   │   │           │   ├── Turn_Right_180_Quad.uasset
│   │   │   │   │           │   ├── Turn_Right_90_Biped.uasset
│   │   │   │   │           │   └── Turn_Right_90_Quad.uasset
│   │   │   │   │           ├── Materials
│   │   │   │   │           │   ├── MI_Rampage_Refract.uasset
│   │   │   │   │           │   ├── M_Rampage_Armor.uasset
│   │   │   │   │           │   ├── M_Rampage_head_legs_Skin_Inst.uasset
│   │   │   │   │           │   ├── M_Rampage_Skin_Arm_Inst.uasset
│   │   │   │   │           │   ├── M_RampageSkin_MASTER.uasset
│   │   │   │   │           │   ├── M_Rampage_Teeth.uasset
│   │   │   │   │           │   ├── M_Rampage_Torso_Inst.uasset
│   │   │   │   │           │   └── SteelSubsurfaceProfileRampage.uasset
│   │   │   │   │           ├── Meshes
│   │   │   │   │           │   ├── ABP_FInalBoss.uasset
│   │   │   │   │           │   ├── Rampage_CylShadows.uasset
│   │   │   │   │           │   ├── Rampage_Extents.uasset
│   │   │   │   │           │   ├── Rampage_Skeleton.uasset
│   │   │   │   │           │   ├── Rampage.uasset
│   │   │   │   │           │   └── Rocks
│   │   │   │   │           │       └── SM_Rock_To_Hold.uasset
│   │   │   │   │           ├── Skins
│   │   │   │   │           │   └── Tier2
│   │   │   │   │           │       └── Elemental
│   │   │   │   │           │           ├── Materials
│   │   │   │   │           │           │   ├── Material_Functions
│   │   │   │   │           │           │   │   └── MF_Float_Rock_Anim.uasset
│   │   │   │   │           │           │   ├── M_RampageElemental_Arms_Inst_Anim.uasset
│   │   │   │   │           │           │   ├── M_RampageElemental_Arms_Inst.uasset
│   │   │   │   │           │           │   ├── M_Rampage_Elemental_FireSplines.uasset
│   │   │   │   │           │           │   ├── M_RampageV001_Legs_Inst.uasset
│   │   │   │   │           │           │   ├── M_RampageV001_MASTER_Inst_Anim.uasset
│   │   │   │   │           │           │   ├── M_RampageV001_MASTER_Inst.uasset
│   │   │   │   │           │           │   ├── M_RampageV001_MASTER.uasset
│   │   │   │   │           │           │   └── M_RampageV001_Torso_Inst.uasset
│   │   │   │   │           │           ├── Meshes
│   │   │   │   │           │           │   └── Rampage_Elemental.uasset
│   │   │   │   │           │           └── Textures
│   │   │   │   │           │               ├── T_Rampage_V001_UV00_Head_Back_Mask.uasset
│   │   │   │   │           │               ├── T_Rampage_V001_UV00_Head_Back_normals.uasset
│   │   │   │   │           │               ├── T_Rampage_V001_UV01_Torso_Mask1.uasset
│   │   │   │   │           │               ├── T_Rampage_V001_UV01_Torso_Mask.uasset
│   │   │   │   │           │               ├── T_Rampage_V001_UV01_Torso_normals.uasset
│   │   │   │   │           │               ├── T_Rampage_V001_UV02_Leg_Shoulder_Mask1.uasset
│   │   │   │   │           │               ├── T_Rampage_V001_UV02_LegShoulder_normal.uasset
│   │   │   │   │           │               ├── T_Rampage_V001_UV02_Leg_Shoulders_Mask.uasset
│   │   │   │   │           │               ├── T_Rampage_V001_UV03_Arms_Mask1.uasset
│   │   │   │   │           │               ├── T_Rampage_V001_UV03_Arms_Mask.uasset
│   │   │   │   │           │               └── T_Rampage_V001_UV03_Arms_normals.uasset
│   │   │   │   │           ├── Sounds
│   │   │   │   │           │   ├── DialogueVoices
│   │   │   │   │           │   │   └── Rampage.uasset
│   │   │   │   │           │   ├── DialogueWaves
│   │   │   │   │           │   │   ├── Rampage_Effort_Attack_01_Dialogue.uasset
│   │   │   │   │           │   │   ├── Rampage_Effort_Attack_03_Dialogue.uasset
│   │   │   │   │           │   │   ├── Rampage_Effort_Attack_04_Dialogue.uasset
│   │   │   │   │           │   │   ├── Rampage_Effort_BreathingRun_02_Dialogue.uasset
│   │   │   │   │           │   │   ├── Rampage_Effort_Laugh_02_Dialogue.uasset
│   │   │   │   │           │   │   ├── Rampage_Effort_Laugh_03_Dialogue.uasset
│   │   │   │   │           │   │   ├── Rampage_Effort_Laugh_07_Dialogue.uasset
│   │   │   │   │           │   │   ├── Rampage_Effort_Laugh_12_Dialogue.uasset
│   │   │   │   │           │   │   ├── Rampage_Effort_Laugh_16_Dialogue.uasset
│   │   │   │   │           │   │   ├── Rampage_Effort_Pain_01_Dialogue.uasset
│   │   │   │   │           │   │   ├── Rampage_Effort_Pain_02_Dialogue.uasset
│   │   │   │   │           │   │   └── Rampage_Effort_Pain_03_Dialogue.uasset
│   │   │   │   │           │   ├── SoundCues
│   │   │   │   │           │   │   ├── Rampage_Effort_Attack.uasset
│   │   │   │   │           │   │   ├── Rampage_Effort_BreathingRun.uasset
│   │   │   │   │           │   │   ├── Rampage_Effort_Laugh.uasset
│   │   │   │   │           │   │   └── Rampage_Effort_Pain.uasset
│   │   │   │   │           │   └── SoundWaves
│   │   │   │   │           │       ├── Rampage_Effort_Attack_01.uasset
│   │   │   │   │           │       ├── Rampage_Effort_Attack_03.uasset
│   │   │   │   │           │       ├── Rampage_Effort_Attack_04.uasset
│   │   │   │   │           │       ├── Rampage_Effort_BreathingRun_02.uasset
│   │   │   │   │           │       ├── Rampage_Effort_Laugh_02.uasset
│   │   │   │   │           │       ├── Rampage_Effort_Laugh_03.uasset
│   │   │   │   │           │       ├── Rampage_Effort_Laugh_07.uasset
│   │   │   │   │           │       ├── Rampage_Effort_Laugh_12.uasset
│   │   │   │   │           │       ├── Rampage_Effort_Laugh_16.uasset
│   │   │   │   │           │       ├── Rampage_Effort_Pain_01.uasset
│   │   │   │   │           │       ├── Rampage_Effort_Pain_02.uasset
│   │   │   │   │           │       └── Rampage_Effort_Pain_03.uasset
│   │   │   │   │           └── Textures
│   │   │   │   │               ├── T_EyeIrisBaseColor_Example_7.uasset
│   │   │   │   │               ├── T_Rampage_Arm_D.uasset
│   │   │   │   │               ├── T_Rampage_Arm_N.uasset
│   │   │   │   │               ├── T_Rampage_Armor_MatMask.uasset
│   │   │   │   │               ├── T_Rampage_Armor_N.uasset
│   │   │   │   │               ├── T_Rampage_Arm_T.uasset
│   │   │   │   │               ├── T_Rampage_Cells_M.uasset
│   │   │   │   │               ├── T_Rampage_Head_Legs_D.uasset
│   │   │   │   │               ├── T_Rampage_Head_Legs_MatMask.uasset
│   │   │   │   │               ├── T_Rampage_Head_Legs_N.uasset
│   │   │   │   │               ├── T_Rampage_Head_Legs_T.uasset
│   │   │   │   │               ├── T_Rampage_Teeth_Diffuse.uasset
│   │   │   │   │               ├── T_Rampage_Teeth_N.uasset
│   │   │   │   │               ├── T_Rampage_Torso_D.uasset
│   │   │   │   │               ├── T_Rampage_Torso_N.uasset
│   │   │   │   │               └── T_Rampage_Torso_T.uasset
│   │   │   │   ├── Blueprints
│   │   │   │   │   ├── BP_BigMeteorAttack.uasset
│   │   │   │   │   ├── BP_BossDrop.uasset
│   │   │   │   │   ├── BP_BossMeteor.uasset
│   │   │   │   │   ├── BP_BossRock.uasset
│   │   │   │   │   ├── BP_DistanceAttack.uasset
│   │   │   │   │   └── BP_EnemyBoss.uasset
│   │   │   │   └── Sequence
│   │   │   │       ├── BossEntrySequence.uasset
│   │   │   │       └── WinEndGame.uasset
│   │   │   ├── EnemySpecialDamage
│   │   │   │   ├── Blueprints
│   │   │   │   │   ├── BP_BossDropTest1.uasset
│   │   │   │   │   ├── BP_SpecialDamage1.uasset
│   │   │   │   │   ├── BP_SpecialDamage2.uasset
│   │   │   │   │   ├── BP_SpecialDamageOneDrop.uasset
│   │   │   │   │   ├── BP_SpecialDamageOne.uasset
│   │   │   │   │   ├── BP_SpecialDamageTwoDrop.uasset
│   │   │   │   │   ├── BP_SpecialDamageTwo.uasset
│   │   │   │   │   └── CR_BigDamage.uasset
│   │   │   │   └── Characters
│   │   │   │       ├── BigDamageAssets
│   │   │   │       │   ├── BigDamage1
│   │   │   │       │   │   ├── Animations
│   │   │   │       │   │   │   ├── Ability_Enrage_Start.uasset
│   │   │   │       │   │   │   ├── AimOffsets
│   │   │   │       │   │   │   │   ├── Aim_CC.uasset
│   │   │   │       │   │   │   │   ├── Aim_CD.uasset
│   │   │   │       │   │   │   │   ├── Aim_CU.uasset
│   │   │   │       │   │   │   │   ├── Aim_LC.uasset
│   │   │   │       │   │   │   │   ├── Aim_LD.uasset
│   │   │   │       │   │   │   │   ├── Aim_LU.uasset
│   │   │   │       │   │   │   │   ├── Aim_RC.uasset
│   │   │   │       │   │   │   │   ├── Aim_RD.uasset
│   │   │   │       │   │   │   │   ├── Aim_RU.uasset
│   │   │   │       │   │   │   │   └── NewAimOffsetBlendSpace.uasset
│   │   │   │       │   │   │   ├── AM_DanceDamage.uasset
│   │   │   │       │   │   │   ├── AM_DetectPlayer.uasset
│   │   │   │       │   │   │   ├── AM_RoarAnimMutant_Roaring_Montage.uasset
│   │   │   │       │   │   │   ├── AM_RoarAnimMutant_Roaring.uasset
│   │   │   │       │   │   │   ├── AS_Hip_Hop_Dancing__1_.uasset
│   │   │   │       │   │   │   ├── Blendspaces
│   │   │   │       │   │   │   │   └── MovementBlends.uasset
│   │   │   │       │   │   │   ├── Hit_Back.uasset
│   │   │   │       │   │   │   ├── Hit_Front.uasset
│   │   │   │       │   │   │   ├── Hit_Left.uasset
│   │   │   │       │   │   │   ├── Hit_Right.uasset
│   │   │   │       │   │   │   ├── Idle.uasset
│   │   │   │       │   │   │   ├── Knock_Bwd.uasset
│   │   │   │       │   │   │   ├── Knock_Fwd.uasset
│   │   │   │       │   │   │   ├── Run_Back.uasset
│   │   │   │       │   │   │   ├── Run_Fwd.uasset
│   │   │   │       │   │   │   ├── Run_Left.uasset
│   │   │   │       │   │   │   ├── Run_Right.uasset
│   │   │   │       │   │   │   ├── Stunned.uasset
│   │   │   │       │   │   │   ├── Turn_Left_180.uasset
│   │   │   │       │   │   │   ├── Turn_Left_90.uasset
│   │   │   │       │   │   │   ├── Turn_Right_180.uasset
│   │   │   │       │   │   │   └── Turn_Right_90.uasset
│   │   │   │       │   │   ├── Blueprints
│   │   │   │       │   │   │   └── ABP_BigDamage1.uasset
│   │   │   │       │   │   ├── Materials
│   │   │   │       │   │   │   ├── M_Green_Buff_LavaDrip.uasset
│   │   │   │       │   │   │   ├── M_GreenBuff.uasset
│   │   │   │       │   │   │   └── T_Greenbuff_LUT.uasset
│   │   │   │       │   │   ├── Meshes
│   │   │   │       │   │   │   ├── Buff_Green_CylShadows.uasset
│   │   │   │       │   │   │   ├── Buff_Green_Skeleton.uasset
│   │   │   │       │   │   │   └── Buff_Green.uasset
│   │   │   │       │   │   └── Textures
│   │   │   │       │   │       ├── T_SmallFlower01_N.uasset
│   │   │   │       │   │       └── T_SmallFlower01.uasset
│   │   │   │       │   └── BigDamage2
│   │   │   │       │       ├── Animations
│   │   │   │       │       │   ├── AimOffsets
│   │   │   │       │       │   │   ├── Aim_CC.uasset
│   │   │   │       │       │   │   ├── Aim_CD.uasset
│   │   │   │       │       │   │   ├── Aim_CU.uasset
│   │   │   │       │       │   │   ├── Aim_LC.uasset
│   │   │   │       │       │   │   ├── Aim_LD.uasset
│   │   │   │       │       │   │   ├── Aim_LU.uasset
│   │   │   │       │       │   │   ├── Aim_RC.uasset
│   │   │   │       │       │   │   ├── Aim_RD.uasset
│   │   │   │       │       │   │   ├── Aim_RU.uasset
│   │   │   │       │       │   │   └── NewAimOffsetBlendSpace.uasset
│   │   │   │       │       │   ├── AM_Attack_Punch_01_Montage.uasset
│   │   │   │       │       │   ├── AM_Attack_Punch_02_Montage.uasset
│   │   │   │       │       │   ├── AM_Attack_SmallCombo_Montage.uasset
│   │   │   │       │       │   ├── AM_Attack_Uppercut_Montage.uasset
│   │   │   │       │       │   ├── AM_BigAttackMontage.uasset
│   │   │   │       │       │   ├── AM_DanceDamage.uasset
│   │   │   │       │       │   ├── AS_Ability_GroundSmash_End.uasset
│   │   │   │       │       │   ├── AS_Ability_GroundSmash_Loop.uasset
│   │   │   │       │       │   ├── AS_Ability_GroundSmash_Start.uasset
│   │   │   │       │       │   ├── AS_Hip_Hop_Dancing__1_.uasset
│   │   │   │       │       │   ├── Attack_BigSmash.uasset
│   │   │   │       │       │   ├── Attack_Punch_01.uasset
│   │   │   │       │       │   ├── Attack_Punch_02.uasset
│   │   │   │       │       │   ├── Attack_SmallCombo.uasset
│   │   │   │       │       │   ├── Attack_Uppercut.uasset
│   │   │   │       │       │   ├── Blendspaces
│   │   │   │       │       │   │   ├── CombatAims.uasset
│   │   │   │       │       │   │   └── MovementBlends.uasset
│   │   │   │       │       │   ├── Death_Back.uasset
│   │   │   │       │       │   ├── Death_Fwd.uasset
│   │   │   │       │       │   ├── Hit_Back.uasset
│   │   │   │       │       │   ├── Hit_Front.uasset
│   │   │   │       │       │   ├── Hit_Left.uasset
│   │   │   │       │       │   ├── Hit_Right.uasset
│   │   │   │       │       │   ├── Idle.uasset
│   │   │   │       │       │   ├── Idle_Variant_01.uasset
│   │   │   │       │       │   ├── Knock_Bwd.uasset
│   │   │   │       │       │   ├── Knock_Fwd.uasset
│   │   │   │       │       │   ├── Run_Back.uasset
│   │   │   │       │       │   ├── Run_Fwd.uasset
│   │   │   │       │       │   ├── Run_Left.uasset
│   │   │   │       │       │   ├── Run_Right.uasset
│   │   │   │       │       │   ├── Spawn.uasset
│   │   │   │       │       │   ├── Stunned.uasset
│   │   │   │       │       │   ├── Turn_Left_180.uasset
│   │   │   │       │       │   ├── Turn_Left_90.uasset
│   │   │   │       │       │   ├── Turn_Right_180.uasset
│   │   │   │       │       │   └── Turn_Right_90.uasset
│   │   │   │       │       ├── Blueprints
│   │   │   │       │       │   └── ABP_BigDamage2.uasset
│   │   │   │       │       ├── Materials
│   │   │   │       │       │   ├── M_Red_Buff_LavaDrip.uasset
│   │   │   │       │       │   └── M_RedBuff.uasset
│   │   │   │       │       ├── Meshes
│   │   │   │       │       │   ├── Buff_Red_CylShadows.uasset
│   │   │   │       │       │   ├── Buff_Red_Skeleton.uasset
│   │   │   │       │       │   └── Buff_Red.uasset
│   │   │   │       │       └── Textures
│   │   │   │       │           ├── T_Buff_Red_D.uasset
│   │   │   │       │           ├── T_Buff_Red_FXMask.uasset
│   │   │   │       │           ├── T_Buff_Red_Height.uasset
│   │   │   │       │           ├── T_Buff_Red_M.uasset
│   │   │   │       │           ├── T_BuffRed_N.uasset
│   │   │   │       │           ├── T_LavaDrip_M.uasset
│   │   │   │       │           ├── T_LavaDrip_N.uasset
│   │   │   │       │           ├── T_LavaRocks.uasset
│   │   │   │       │           ├── T_MicroCrackle_M.uasset
│   │   │   │       │           ├── T_MicroCrackle_N.uasset
│   │   │   │       │           ├── T_SwirlNoise.uasset
│   │   │   │       │           └── T_Water2_M.uasset
│   │   │   │       └── Global
│   │   │   │           ├── Animations
│   │   │   │           │   ├── Attack_BigSmash.uasset
│   │   │   │           │   ├── Attack_Punch_01.uasset
│   │   │   │           │   ├── Attack_Punch_02.uasset
│   │   │   │           │   ├── Attack_SmallCombo.uasset
│   │   │   │           │   └── Attack_Uppercut.uasset
│   │   │   │           ├── FX
│   │   │   │           │   └── Textures
│   │   │   │           │       └── Water
│   │   │   │           │           └── T_Caustics_Softer.uasset
│   │   │   │           ├── MaterialFunctions
│   │   │   │           │   ├── HitFlash.uasset
│   │   │   │           │   ├── MaterialLayerConstructors
│   │   │   │           │   │   ├── MLC_ScratchAndGrime.uasset
│   │   │   │           │   │   └── MLC_Standard.uasset
│   │   │   │           │   ├── MF_BrightnessAdjust.uasset
│   │   │   │           │   ├── MF_CharacterEffects.uasset
│   │   │   │           │   ├── MF_DeathFade.uasset
│   │   │   │           │   ├── MF_OrionRimlight.uasset
│   │   │   │           │   └── Textures
│   │   │   │           │       ├── T_AtmosphericCloudNoise01_N.uasset
│   │   │   │           │       ├── T_AtmosphericCloudNoise01.uasset
│   │   │   │           │       ├── T_AtmosphericCloudNoise03.uasset
│   │   │   │           │       └── T_Plasma_Noise.uasset
│   │   │   │           ├── MaterialLayers
│   │   │   │           │   ├── Foliage
│   │   │   │           │   │   ├── T_TilingMoss_Clovers-n-Flowers_02_D.uasset
│   │   │   │           │   │   └── T_TilingMoss_Clovers-n-Flowers_02_N.uasset
│   │   │   │           │   ├── Metal
│   │   │   │           │   │   ├── ML_blue_Metal.uasset
│   │   │   │           │   │   └── T_Blue_Metal02.uasset
│   │   │   │           │   ├── ML__Blank.uasset
│   │   │   │           │   ├── Rubber
│   │   │   │           │   │   └── T_Blank_N.uasset
│   │   │   │           │   ├── Special
│   │   │   │           │   │   └── T_LavaFloor_02_D.uasset
│   │   │   │           │   ├── T_TestML_Mask.uasset
│   │   │   │           │   └── Wood
│   │   │   │           │       ├── ML_Moss.uasset
│   │   │   │           │       ├── ML_TreeBark.uasset
│   │   │   │           │       ├── T_TreeBark_D.uasset
│   │   │   │           │       └── T_TreeBark_N.uasset
│   │   │   │           └── ParameterCollections
│   │   │   │               └── OrionGlobalGameplayCollection.uasset
│   │   │   ├── EnemySpecialTank
│   │   │   │   ├── Assets
│   │   │   │   │   └── Golem
│   │   │   │   │       ├── GolemAnimation
│   │   │   │   │       │   ├── AM_GolemAttackMontage.uasset
│   │   │   │   │       │   ├── AM_Mutant_Roaring_Montage.uasset
│   │   │   │   │       │   ├── AM_Mutant_Roaring.uasset
│   │   │   │   │       │   ├── AM_TankCombo.uasset
│   │   │   │   │       │   ├── AM_TankDance.uasset
│   │   │   │   │       │   ├── AM_TankPunch1.uasset
│   │   │   │   │       │   ├── AM_TankPunch2.uasset
│   │   │   │   │       │   ├── AM_TankPunch3.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Attack_1.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Attack_2.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Attack_3.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Attack_4.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Attack_5.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Attack_6.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Attack_7.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Attack_8.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Dead_1.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Dead_2.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Dead_3.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Dead_4.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Get_Hit_1.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Get_Hit_2.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Idle_Other_02.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Idle_Othe.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Idle_Sit.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Idle.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Jump.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Run_Back.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Run_Left.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Run_Right.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Run.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Shout.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Take_Weapon.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Turn_left_Sit.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Turn_left.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Turn_Right_Sit.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Turn_Right.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Walk_Back_Sit.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Walk_Back.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Walk_Left_Sit.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Walk_Left.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Walk_Right.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Walk_Sit_Right.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Walk_Sit.uasset
│   │   │   │   │       │   ├── Anim_Warrior_Walk.uasset
│   │   │   │   │       │   ├── AS_Ability_GroundSmash_End.uasset
│   │   │   │   │       │   ├── AS_Ability_GroundSmash_Loop.uasset
│   │   │   │   │       │   ├── AS_Ability_GroundSmash_Start.uasset
│   │   │   │   │       │   ├── AS_Hip_Hop_Dancing__1_.uasset
│   │   │   │   │       │   ├── AS_JumpIdle.uasset
│   │   │   │   │       │   ├── Attack_Punch_01.uasset
│   │   │   │   │       │   ├── Attack_Punch_02.uasset
│   │   │   │   │       │   ├── Attack_SmallCombo.uasset
│   │   │   │   │       │   ├── Attack_Uppercut.uasset
│   │   │   │   │       │   ├── Idle.uasset
│   │   │   │   │       │   ├── MovementBlends.uasset
│   │   │   │   │       │   ├── Run_Back.uasset
│   │   │   │   │       │   ├── Run_Fwd.uasset
│   │   │   │   │       │   ├── Run_Left.uasset
│   │   │   │   │       │   └── Run_Right.uasset
│   │   │   │   │       ├── Material
│   │   │   │   │       │   └── M_Golem.uasset
│   │   │   │   │       ├── Mesh
│   │   │   │   │       │   ├── ABP_EnemyTank.uasset
│   │   │   │   │       │   ├── SK_Golem_PhysicsAsset.uasset
│   │   │   │   │       │   ├── SK_Golem_Skeleton.uasset
│   │   │   │   │       │   └── SK_Golem.uasset
│   │   │   │   │       └── Textures
│   │   │   │   │           ├── T_Golem_Albedo.uasset
│   │   │   │   │           ├── T_Golem_Ao.uasset
│   │   │   │   │           ├── T_Golem_Metallic.uasset
│   │   │   │   │           └── T_Golem_Normals.uasset
│   │   │   │   └── Blueprint
│   │   │   │       ├── BP_SpecialTankEnemy.uasset
│   │   │   │       ├── BP_SpecialTankPickUp.uasset
│   │   │   │       ├── BP_SpecialTank.uasset
│   │   │   │       └── CR_Tank.uasset
│   │   │   └── Global
│   │   │       ├── Assets
│   │   │       │   └── SM_BasicRock.uasset
│   │   │       ├── IA
│   │   │       │   ├── BasicEnemy
│   │   │       │   │   ├── BB_EnemyBasic.uasset
│   │   │       │   │   ├── BP_BaseEnemyIAController.uasset
│   │   │       │   │   ├── BT_BasicEnemy.uasset
│   │   │       │   │   ├── BTTask_Dance.uasset
│   │   │       │   │   └── BTTask_RandomLocationPatrol.uasset
│   │   │       │   ├── Boss
│   │   │       │   │   ├── BB_BossEnemy.uasset
│   │   │       │   │   ├── BossPhase.uasset
│   │   │       │   │   ├── BP_BossEnemyController.uasset
│   │   │       │   │   ├── BT_BossEnemy.uasset
│   │   │       │   │   ├── BTTask_BigMeteorAttack.uasset
│   │   │       │   │   ├── BTTask_DistanceAttack.uasset
│   │   │       │   │   ├── BTTask_RandomLocationPatrolBoss.uasset
│   │   │       │   │   ├── BTTS_PlayDestruction.uasset
│   │   │       │   │   ├── BTTS_PlayEnrageAnimation.uasset
│   │   │       │   │   └── DestructionCurve.uasset
│   │   │       │   └── SpecialDamageEnemies
│   │   │       │       ├── BB_SpecialEnemy.uasset
│   │   │       │       ├── BP_SpecialEnemyController.uasset
│   │   │       │       ├── BT_SpecialEnemy.uasset
│   │   │       │       ├── BTTask_PlayRoarAnimation.uasset
│   │   │       │       └── BTTask_RandomLocationPatrolSpecial.uasset
│   │   │       ├── Notifies
│   │   │       │   ├── BP_BigMeteorAttack.uasset
│   │   │       │   ├── BP_BowlingMeteor.uasset
│   │   │       │   ├── BP_DistanceAttack.uasset
│   │   │       │   ├── BP_EnemyAttackAnimNotifyState.uasset
│   │   │       │   ├── BP_EnemyAttacKReset.uasset
│   │   │       │   ├── BP_PickUpRock.uasset
│   │   │       │   ├── BP_PlayRoarSound.uasset
│   │   │       │   ├── BP_PlaySoundAtLocation.uasset
│   │   │       │   └── BP_TossRock.uasset
│   │   │       └── UI
│   │   │           ├── HealthBar.uasset
│   │   │           └── WBP_EnemyHealthBar.uasset
│   │   ├── Mannequin_UE4
│   │   │   ├── Materials
│   │   │   │   ├── Layers
│   │   │   │   │   ├── ML_Latex_Black.uasset
│   │   │   │   │   ├── ML_ShinyPlastic_Beige_Logo.uasset
│   │   │   │   │   ├── ML_ShinyPlastic_Beige.uasset
│   │   │   │   │   └── ML_SoftMetal.uasset
│   │   │   │   ├── M_MannequinUE4_Body.uasset
│   │   │   │   └── M_MannequinUE4_ChestLogo.uasset
│   │   │   ├── Meshes
│   │   │   │   ├── SK_Mannequin_PhysicsAsset.uasset
│   │   │   │   ├── SK_Mannequin_Skeleton.uasset
│   │   │   │   └── SK_Mannequin.uasset
│   │   │   ├── MixamoCharacter
│   │   │   │   ├── Beta_HighLimbsGeoSG3.uasset
│   │   │   │   ├── Beta_Joints_MAT1.uasset
│   │   │   │   ├── IK_X_Bot.uasset
│   │   │   │   ├── MixamoAnim
│   │   │   │   │   ├── Beta_HighLimbsGeoSG3.uasset
│   │   │   │   │   ├── Beta_Joints_MAT1.uasset
│   │   │   │   │   ├── Breakdance_Freezes_Anim_mixamo_com.uasset
│   │   │   │   │   ├── Breakdance_Freezes_Anim_Take_001.uasset
│   │   │   │   │   ├── Breakdance_Freezes_PhysicsAsset.uasset
│   │   │   │   │   ├── Breakdance_Freezes.uasset
│   │   │   │   │   ├── Chicken_Dance.uasset
│   │   │   │   │   ├── Flair.uasset
│   │   │   │   │   ├── Great_Sword_Impact.uasset
│   │   │   │   │   ├── Hip_Hop_Dancing__1_.uasset
│   │   │   │   │   ├── Hip_Hop_Dancing.uasset
│   │   │   │   │   ├── Moonwalk.uasset
│   │   │   │   │   ├── Mutant_Roaring.uasset
│   │   │   │   │   ├── Standing_1H_Magic_Attack_03.uasset
│   │   │   │   │   ├── Standing_2H_Magic_Area_Attack_01.uasset
│   │   │   │   │   ├── Standing_React_Small_From_Right.uasset
│   │   │   │   │   ├── Standing_Taunt_Battlecry.uasset
│   │   │   │   │   └── Wide_Arm_Spell_Casting.uasset
│   │   │   │   ├── RetargetedAnimations
│   │   │   │   │   ├── AM_Hip_Hop_Dancing.uasset
│   │   │   │   │   ├── AM_Mutant_Roaring.uasset
│   │   │   │   │   ├── AS_Hip_Hop_Dancing__1_.uasset
│   │   │   │   │   ├── IK_AutoGeneratedSource.uasset
│   │   │   │   │   ├── IK_AutoGeneratedTarget.uasset
│   │   │   │   │   └── RTG_AutoGenerated.uasset
│   │   │   │   ├── RTG_X_Bot.uasset
│   │   │   │   ├── X_Bot_PhysicsAsset.uasset
│   │   │   │   ├── X_Bot_Skeleton.uasset
│   │   │   │   └── X_Bot.uasset
│   │   │   └── Textures
│   │   │       ├── T_ML_Aluminum01_N.uasset
│   │   │       ├── T_ML_Aluminum01.uasset
│   │   │       ├── T_ML_Rubber_Blue_01_D.uasset
│   │   │       ├── T_ML_Rubber_Blue_01_N.uasset
│   │   │       ├── T_UE4_Mannequin_MAT_MASKA.uasset
│   │   │       ├── T_UE4_Mannequin__normals.uasset
│   │   │       ├── T_UELogo_Mask.uasset
│   │   │       └── T_UELogo_N_TGA.uasset
│   │   ├── PlayerCharacter
│   │   │   ├── Blueprints
│   │   │   │   ├── ABP_PlayerCharacterAnimBlueprint.uasset
│   │   │   │   ├── BP_PlayerCharacter.uasset
│   │   │   │   ├── Controllers
│   │   │   │   │   ├── IMC_PlayerInputmap.uasset
│   │   │   │   │   └── Input
│   │   │   │   │       ├── IA_Attack.uasset
│   │   │   │   │       ├── IA_Dodge.uasset
│   │   │   │   │       ├── IA_Interact.uasset
│   │   │   │   │       ├── IA_Jump.uasset
│   │   │   │   │       ├── IA_LockOnEnemy.uasset
│   │   │   │   │       ├── IA_Look.uasset
│   │   │   │   │       ├── IA_Move.uasset
│   │   │   │   │       ├── IA_PauseGame.uasset
│   │   │   │   │       ├── IA_Run.uasset
│   │   │   │   │       └── IA_ToggleWeapon.uasset
│   │   │   │   ├── CR_PlayerCharacterRig.uasset
│   │   │   │   └── IU
│   │   │   │       ├── BP_PlayerHUDClass.uasset
│   │   │   │       ├── UI_Curves
│   │   │   │       │   └── C_HealthBarUpdate.uasset
│   │   │   │       ├── UI_Textures
│   │   │   │       │   ├── DeadImage.uasset
│   │   │   │       │   ├── FireballWeapon.uasset
│   │   │   │       │   ├── HandWeapon.uasset
│   │   │   │       │   ├── HealthBarDecoration.uasset
│   │   │   │       │   ├── HealthBarGradient.uasset
│   │   │   │       │   └── SwordWeapon.uasset
│   │   │   │       ├── WBP_EndGame.uasset
│   │   │   │       ├── WBP_InteractionWidget.uasset
│   │   │   │       ├── WBP_PlayerGameplayUI.uasset
│   │   │   │       ├── WBP_SettingsMenu.uasset
│   │   │   │       └── WBP_WinGame.uasset
│   │   │   ├── CharacterAssets
│   │   │   │   ├── CharacterMeshAssets
│   │   │   │   │   ├── Animations
│   │   │   │   │   │   ├── ArmedMovement
│   │   │   │   │   │   │   ├── BS_ArmedMovement.uasset
│   │   │   │   │   │   │   ├── Idle.uasset
│   │   │   │   │   │   │   ├── Jog_Bwd_CircleLeft.uasset
│   │   │   │   │   │   │   ├── Jog_Bwd_CircleRight.uasset
│   │   │   │   │   │   │   ├── Jog_Bwd.uasset
│   │   │   │   │   │   │   ├── Jog_Fwd_CircleLeft.uasset
│   │   │   │   │   │   │   ├── Jog_Fwd_CircleRight.uasset
│   │   │   │   │   │   │   ├── Jog_Fwd.uasset
│   │   │   │   │   │   │   ├── Jog_Left.uasset
│   │   │   │   │   │   │   └── Jog_Right.uasset
│   │   │   │   │   │   ├── AS_Breakdance_Freezes_Anim_mixamo_com.uasset
│   │   │   │   │   │   ├── Combat
│   │   │   │   │   │   │   ├── AM_CastBigSpellMontage.uasset
│   │   │   │   │   │   │   ├── AM_CastFastSpell1_Montage.uasset
│   │   │   │   │   │   │   ├── AM_DeathMontage.uasset
│   │   │   │   │   │   │   ├── AM_MeleeAttack1Montage.uasset
│   │   │   │   │   │   │   ├── AM_MeleeAttack2Montage.uasset
│   │   │   │   │   │   │   ├── AM_MeleeAttack3Montage.uasset
│   │   │   │   │   │   │   ├── AM_MeleeAttack4Montage.uasset
│   │   │   │   │   │   │   ├── AM_ToggleWeaponFinal_Montage.uasset
│   │   │   │   │   │   │   ├── AS_CastBigSpell.uasset
│   │   │   │   │   │   │   ├── AS_CastFastSpell1.uasset
│   │   │   │   │   │   │   ├── AS_DeathAnim.uasset
│   │   │   │   │   │   │   ├── AS_EquipWeapon.uasset
│   │   │   │   │   │   │   ├── AS_Great_Sword_Impact_Montage.uasset
│   │   │   │   │   │   │   ├── AS_Great_Sword_Impact.uasset
│   │   │   │   │   │   │   ├── AS_MeleeAttack1.uasset
│   │   │   │   │   │   │   ├── AS_MeleeAttack2.uasset
│   │   │   │   │   │   │   ├── AS_MeleeAttack3.uasset
│   │   │   │   │   │   │   ├── AS_MeleeAttack4.uasset
│   │   │   │   │   │   │   ├── AS_Standing_React_Small_From_Right_Montage.uasset
│   │   │   │   │   │   │   ├── AS_Standing_React_Small_From_Right.uasset
│   │   │   │   │   │   │   ├── AS_ToggleWeaponFinal.uasset
│   │   │   │   │   │   │   └── AS_ToggleWeapon.uasset
│   │   │   │   │   │   ├── Dodge
│   │   │   │   │   │   │   ├── AM_DodgeBack.uasset
│   │   │   │   │   │   │   ├── AM_Dodge_B.uasset
│   │   │   │   │   │   │   ├── AM_DodgeForward.uasset
│   │   │   │   │   │   │   ├── AM_Dodge_F.uasset
│   │   │   │   │   │   │   ├── AM_DodgeLeft.uasset
│   │   │   │   │   │   │   ├── AM_Dodge_L.uasset
│   │   │   │   │   │   │   ├── AM_DodgeRight.uasset
│   │   │   │   │   │   │   └── AM_Dodge_R.uasset
│   │   │   │   │   │   ├── Jump
│   │   │   │   │   │   │   ├── AS_GK_AS_FallLoop.uasset
│   │   │   │   │   │   │   ├── AS_GK_AS_Jump.uasset
│   │   │   │   │   │   │   └── AS_GK_AS_Land.uasset
│   │   │   │   │   │   ├── Movement
│   │   │   │   │   │   │   ├── BS_Movement.uasset
│   │   │   │   │   │   │   ├── M_Neutral_Run_Loop_B1.uasset
│   │   │   │   │   │   │   ├── M_Neutral_Run_Loop_BL1.uasset
│   │   │   │   │   │   │   ├── M_Neutral_Run_Loop_BR1.uasset
│   │   │   │   │   │   │   ├── M_Neutral_Run_Loop_F1.uasset
│   │   │   │   │   │   │   ├── M_Neutral_Run_Loop_FL1.uasset
│   │   │   │   │   │   │   ├── M_Neutral_Run_Loop_FR1.uasset
│   │   │   │   │   │   │   ├── M_Neutral_Run_Loop_LL1.uasset
│   │   │   │   │   │   │   ├── M_Neutral_Run_Loop_LR1.uasset
│   │   │   │   │   │   │   ├── M_Neutral_Run_Loop_RL1.uasset
│   │   │   │   │   │   │   ├── M_Neutral_Stand_Idle_Loop1.uasset
│   │   │   │   │   │   │   ├── NoRootWalkBwd.uasset
│   │   │   │   │   │   │   ├── NoRootWalkLeft.uasset
│   │   │   │   │   │   │   ├── NoRootWalkRght.uasset
│   │   │   │   │   │   │   └── WalkFwd.uasset
│   │   │   │   │   │   └── Notifies
│   │   │   │   │   │       ├── BP_CastSpellNotify.uasset
│   │   │   │   │   │       ├── BP_DeadBroadcast.uasset
│   │   │   │   │   │       ├── BP_EndAttackNotify.uasset
│   │   │   │   │   │       ├── BP_MeleeAttack.uasset
│   │   │   │   │   │       ├── BP_ResetDodge.uasset
│   │   │   │   │   │       ├── BP_ResetHitted.uasset
│   │   │   │   │   │       └── BP_WeaponSwapNotify.uasset
│   │   │   │   │   ├── Materials
│   │   │   │   │   │   ├── Eyes
│   │   │   │   │   │   │   ├── T_EyeBaseColorA_mkt.uasset
│   │   │   │   │   │   │   ├── T_EyeDisplacement_MKT.uasset
│   │   │   │   │   │   │   ├── T_EyeNormals_MKT.uasset
│   │   │   │   │   │   │   ├── T_EyeScleraBaseColor_mkt.uasset
│   │   │   │   │   │   │   ├── T_Eye_Wet_Normal_MKT.uasset
│   │   │   │   │   │   │   └── T_SecondReflection_mkt.uasset
│   │   │   │   │   │   ├── MaterialFunctions
│   │   │   │   │   │   │   └── ML_EyeRefraction.uasset
│   │   │   │   │   │   ├── M_Eye.uasset
│   │   │   │   │   │   ├── MI_BearFur.uasset
│   │   │   │   │   │   ├── MI_EyeMaterial.uasset
│   │   │   │   │   │   ├── MI_GKnight_Body.uasset
│   │   │   │   │   │   ├── MI_GKnightCape.uasset
│   │   │   │   │   │   ├── MI_GKnight_Glove.uasset
│   │   │   │   │   │   ├── MI_GKnight_Helmet.uasset
│   │   │   │   │   │   ├── MI_GKnight_Pants.uasset
│   │   │   │   │   │   ├── MI_GKnightSkirt_hide.uasset
│   │   │   │   │   │   ├── MI_GKnightSkirt.uasset
│   │   │   │   │   │   ├── MI_headD.uasset
│   │   │   │   │   │   ├── M_Master_FurAndHair.uasset
│   │   │   │   │   │   ├── M_MKT_MasterMaterial_v02.uasset
│   │   │   │   │   │   ├── M_Skin_Master.uasset
│   │   │   │   │   │   ├── TestSphere
│   │   │   │   │   │   │   ├── Mesh
│   │   │   │   │   │   │   │   └── LP.uasset
│   │   │   │   │   │   │   └── Textures
│   │   │   │   │   │   │       ├── T_BaseMaterial_v01_D.uasset
│   │   │   │   │   │   │       ├── T_BaseMaterial_v01_ID.uasset
│   │   │   │   │   │   │       ├── T_BaseMaterial_v01_N.uasset
│   │   │   │   │   │   │       └── T_BaseMaterial_v01_ORM.uasset
│   │   │   │   │   │   └── Weapon
│   │   │   │   │   │       └── MI_GKnight_Sword.uasset
│   │   │   │   │   ├── Meshes
│   │   │   │   │   │   ├── Parts
│   │   │   │   │   │   │   └── SK_GothicKnight_CapeFur.uasset
│   │   │   │   │   │   ├── SK_GothicKnight_Physics.uasset
│   │   │   │   │   │   ├── SK_GothicKnight_Skeleton.uasset
│   │   │   │   │   │   └── SK_GothicKnight_VC.uasset
│   │   │   │   │   └── Textures
│   │   │   │   │       ├── BearFur
│   │   │   │   │       │   ├── T_T_FurBear_D.uasset
│   │   │   │   │       │   ├── T_T_FurBear_H.uasset
│   │   │   │   │       │   ├── T_T_FurBear_N.uasset
│   │   │   │   │       │   └── T_T_FurBear_RMOC.uasset
│   │   │   │   │       ├── Body
│   │   │   │   │       │   ├── T_GothicKnight_Body_D.uasset
│   │   │   │   │       │   ├── T_GothicKnight_Body_ID.uasset
│   │   │   │   │       │   ├── T_GothicKnight_Body_N.uasset
│   │   │   │   │       │   └── T_GothicKnight_Body_ORM.uasset
│   │   │   │   │       ├── Decals
│   │   │   │   │       │   ├── T_CoatOfArm_02.uasset
│   │   │   │   │       │   ├── T_CoatOfArm_04_1.uasset
│   │   │   │   │       │   └── T_CoatOfArm_Zero.uasset
│   │   │   │   │       ├── DetailMaps
│   │   │   │   │       │   └── T_detailMap01_n.uasset
│   │   │   │   │       ├── FaceB
│   │   │   │   │       │   ├── T_GHead_B_D.uasset
│   │   │   │   │       │   ├── T_GHead_B_N.uasset
│   │   │   │   │       │   └── T_GHead_B_ORM.uasset
│   │   │   │   │       ├── Gloves
│   │   │   │   │       │   ├── T_GothicKnight_Glove_D.uasset
│   │   │   │   │       │   ├── T_GothicKnight_Glove_ID.uasset
│   │   │   │   │       │   ├── T_GothicKnight_Glove_N.uasset
│   │   │   │   │       │   └── T_GothicKnight_Glove_ORM.uasset
│   │   │   │   │       ├── Helmet
│   │   │   │   │       │   ├── T_GothicKnight_Helmet_D.uasset
│   │   │   │   │       │   ├── T_GothicKnight_Helmet_ID.uasset
│   │   │   │   │       │   ├── T_GothicKnight_Helmet_N.uasset
│   │   │   │   │       │   └── T_GothicKnight_Helmet_ORM.uasset
│   │   │   │   │       ├── KnightCape
│   │   │   │   │       │   ├── T_GothicKnight_CapeD_D.uasset
│   │   │   │   │       │   ├── T_GothicKnight_Cape_ID.uasset
│   │   │   │   │       │   ├── T_GothicKnight_Cape_N.uasset
│   │   │   │   │       │   └── T_GothicKnight_Cape_ORM.uasset
│   │   │   │   │       ├── Pants
│   │   │   │   │       │   ├── T_GothicKnight_Pants_D.uasset
│   │   │   │   │       │   ├── T_GothicKnight_Pants_ID.uasset
│   │   │   │   │       │   ├── T_GothicKnight_Pants_N.uasset
│   │   │   │   │       │   └── T_GothicKnight_Pants_ORM.uasset
│   │   │   │   │       ├── Skirt
│   │   │   │   │       │   ├── T_GothicKnight_SkirtB_D.uasset
│   │   │   │   │       │   ├── T_GothicKnight_Skirt_ID.uasset
│   │   │   │   │       │   └── T_GothicKnight_Skirt_N.uasset
│   │   │   │   │       ├── Tiles
│   │   │   │   │       │   ├── checker.uasset
│   │   │   │   │       │   ├── T_Denim_d.uasset
│   │   │   │   │       │   ├── T_FlatMid.uasset
│   │   │   │   │       │   └── T_Pattern_E.uasset
│   │   │   │   │       └── WP_GothicSword
│   │   │   │   │           ├── T_GothicKnight_Sword_D.uasset
│   │   │   │   │           ├── T_GothicKnight_Sword_ID.uasset
│   │   │   │   │           ├── T_GothicKnight_Sword_N.uasset
│   │   │   │   │           └── T_GothicKnight_Sword_ORM.uasset
│   │   │   │   └── Weapons
│   │   │   │       ├── BP_MasterWeapon.uasset
│   │   │   │       ├── Magic
│   │   │   │       │   ├── Assets
│   │   │   │       │   │   ├── Blueprints
│   │   │   │       │   │   │   ├── BP_ky_darkStorm.uasset
│   │   │   │       │   │   │   ├── BP_ky_magicCircle1.uasset
│   │   │   │       │   │   │   └── BP_ky_storm.uasset
│   │   │   │       │   │   ├── Book_wldobc3
│   │   │   │       │   │   │   ├── MI_Book_wldobc3_1K.uasset
│   │   │   │       │   │   │   ├── S_Book_wldobc3_lod5.uasset
│   │   │   │       │   │   │   ├── T_Book_wldobc3_1K_DpR.uasset
│   │   │   │       │   │   │   ├── T_Book_wldobc3_1K_D.uasset
│   │   │   │       │   │   │   └── T_Book_wldobc3_1K_N.uasset
│   │   │   │       │   │   ├── Book_wleidix
│   │   │   │       │   │   │   ├── MI_Book_wleidix_1K.uasset
│   │   │   │       │   │   │   ├── S_Book_wleidix_lod5.uasset
│   │   │   │       │   │   │   ├── T_Book_wleidix_1K_DpR.uasset
│   │   │   │       │   │   │   ├── T_Book_wleidix_1K_D.uasset
│   │   │   │       │   │   │   └── T_Book_wleidix_1K_N.uasset
│   │   │   │       │   │   ├── Materials
│   │   │   │       │   │   │   ├── Mfunction
│   │   │   │       │   │   │   │   ├── MF_ky_AddHilight.uasset
│   │   │   │       │   │   │   │   ├── MF_ky_MaskToTopUnder.uasset
│   │   │   │       │   │   │   │   ├── MF_ky_TexController_primitive.uasset
│   │   │   │       │   │   │   │   ├── MF_ky_TexController.uasset
│   │   │   │       │   │   │   │   └── MF_ky_VectorToRadialValue.uasset
│   │   │   │       │   │   │   ├── MI_ky_chantDecoAc.uasset
│   │   │   │       │   │   │   ├── MI_ky_circleDust.uasset
│   │   │   │       │   │   │   ├── MI_ky_dynDust.uasset
│   │   │   │       │   │   │   ├── MI_ky_storm01_dark_nonD.uasset
│   │   │   │       │   │   │   ├── MI_ky_storm01_dark.uasset
│   │   │   │       │   │   │   ├── MI_ky_storm01_nonD.uasset
│   │   │   │       │   │   │   ├── MI_ky_stormDeco01_dark.uasset
│   │   │   │       │   │   │   ├── MI_ky_turbulence_smoke2d_trs.uasset
│   │   │   │       │   │   │   ├── MI_ky_vortex04B_4x4_two.uasset
│   │   │   │       │   │   │   ├── M_ky_base_turbulence.uasset
│   │   │   │       │   │   │   ├── M_ky_base.uasset
│   │   │   │       │   │   │   ├── M_ky_chantDecoA.uasset
│   │   │   │       │   │   │   ├── M_ky_circle01_4x4G_nonD.uasset
│   │   │   │       │   │   │   ├── M_ky_dynDust.uasset
│   │   │   │       │   │   │   ├── M_ky_empty.uasset
│   │   │   │       │   │   │   ├── M_ky_flare_flash.uasset
│   │   │   │       │   │   │   ├── M_ky_Fresnel.uasset
│   │   │   │       │   │   │   ├── M_ky_magicCircle020.uasset
│   │   │   │       │   │   │   ├── M_ky_stone02.uasset
│   │   │   │       │   │   │   ├── M_ky_storm01.uasset
│   │   │   │       │   │   │   ├── M_ky_stormDeco01.uasset
│   │   │   │       │   │   │   └── M_ky_vortex04_4x4.uasset
│   │   │   │       │   │   ├── Meshes
│   │   │   │       │   │   │   ├── SM_ky_circleDist06.uasset
│   │   │   │       │   │   │   ├── SM_ky_cylinderBend07.uasset
│   │   │   │       │   │   │   ├── SM_ky_quad_centerRot.uasset
│   │   │   │       │   │   │   └── SM_ky_tornado07.uasset
│   │   │   │       │   │   ├── Particles
│   │   │   │       │   │   │   ├── P_ky_magicCircle1.uasset
│   │   │   │       │   │   │   └── P_ky_storm.uasset
│   │   │   │       │   │   └── Textures
│   │   │   │       │   │       ├── T_ky_auraWallWhite_4x4.uasset
│   │   │   │       │   │       ├── T_ky_chantDecoC.uasset
│   │   │   │       │   │       ├── T_ky_circle01_4x4.uasset
│   │   │   │       │   │       ├── T_ky_circleDust.uasset
│   │   │   │       │   │       ├── T_ky_dist_noise.uasset
│   │   │   │       │   │       ├── T_ky_flare_a.uasset
│   │   │   │       │   │       ├── T_ky_magicCircle020.uasset
│   │   │   │       │   │       ├── T_ky_maskRGB3.uasset
│   │   │   │       │   │       ├── T_ky_noise17.uasset
│   │   │   │       │   │       ├── T_ky_noise3.uasset
│   │   │   │       │   │       ├── T_ky_noise4.uasset
│   │   │   │       │   │       ├── T_ky_noise5.uasset
│   │   │   │       │   │       ├── T_ky_noise6.uasset
│   │   │   │       │   │       ├── T_ky_noise.uasset
│   │   │   │       │   │       ├── T_ky_smoke2.uasset
│   │   │   │       │   │       ├── T_ky_smoke_kai.uasset
│   │   │   │       │   │       ├── T_ky_stone02_2x2.uasset
│   │   │   │       │   │       └── T_ky_vortex04_4x4.uasset
│   │   │   │       │   ├── Blueprints
│   │   │   │       │   │   ├── BP_BaseFireballWeapon.uasset
│   │   │   │       │   │   ├── BP_BaseLightball.uasset
│   │   │   │       │   │   ├── BP_FireStorm.uasset
│   │   │   │       │   │   ├── BP_LightStorm.uasset
│   │   │   │       │   │   ├── BP_MGW_Firespell.uasset
│   │   │   │       │   │   ├── BP_MGW_FireStormSpell.uasset
│   │   │   │       │   │   ├── BP_MGW_LightSpell.uasset
│   │   │   │       │   │   └── BP_MGW_LightStormSpell.uasset
│   │   │   │       │   └── SpellAssets
│   │   │   │       │       ├── Materials
│   │   │   │       │       │   ├── Materials
│   │   │   │       │       │   │   ├── Mfunction
│   │   │   │       │       │   │   │   └── MF_ky_VectorToRadialValue.uasset
│   │   │   │       │       │   │   ├── MI_ky_flare_flash_trs.uasset
│   │   │   │       │       │   │   ├── MI_ky_polar_two.uasset
│   │   │   │       │       │   │   ├── MI_ky_turbulence_smoke2d_trs.uasset
│   │   │   │       │       │   │   ├── M_ky_base_turbulence.uasset
│   │   │   │       │       │   │   ├── M_ky_flare_flash.uasset
│   │   │   │       │       │   │   ├── M_ky_polar.uasset
│   │   │   │       │       │   │   └── M_ky_smoke01.uasset
│   │   │   │       │       │   ├── Mfunction
│   │   │   │       │       │   │   ├── MF_ky_AddHilight.uasset
│   │   │   │       │       │   │   ├── MF_ky_MaskToTopUnder.uasset
│   │   │   │       │       │   │   ├── MF_ky_TexController_primitive.uasset
│   │   │   │       │       │   │   ├── MF_ky_TexController.uasset
│   │   │   │       │       │   │   └── MF_ky_VectorToRadialValue.uasset
│   │   │   │       │       │   ├── MI_ky_dynDust.uasset
│   │   │   │       │       │   ├── MI_ky_flare_flash_trs.uasset
│   │   │   │       │       │   ├── MI_ky_lightning02_4x4.uasset
│   │   │   │       │       │   ├── MI_ky_lightningDust01_4x4_nonD.uasset
│   │   │   │       │       │   ├── MI_ky_polar_two.uasset
│   │   │   │       │       │   ├── MI_ky_primitive2b_trs.uasset
│   │   │   │       │       │   ├── MI_ky_primitive_dynB_two.uasset
│   │   │   │       │       │   ├── MI_ky_shockWave03g_4x4.uasset
│   │   │   │       │       │   ├── MI_ky_smoke01b.uasset
│   │   │   │       │       │   ├── MI_ky_smoke01.uasset
│   │   │   │       │       │   ├── MI_ky_storm01_fire_nonD1.uasset
│   │   │   │       │       │   ├── MI_ky_storm01_fire.uasset
│   │   │   │       │       │   ├── MI_ky_storm01_thunder_nonD.uasset
│   │   │   │       │       │   ├── MI_ky_storm01_thunder.uasset
│   │   │   │       │       │   ├── MI_ky_stormDeco01_fire.uasset
│   │   │   │       │       │   ├── MI_ky_turbulence_smoke2d_trs.uasset
│   │   │   │       │       │   ├── M_ky_base_turbulence.uasset
│   │   │   │       │       │   ├── M_ky_dynDust.uasset
│   │   │   │       │       │   ├── M_ky_empty.uasset
│   │   │   │       │       │   ├── M_ky_flare_flash.uasset
│   │   │   │       │       │   ├── M_ky_polar.uasset
│   │   │   │       │       │   ├── M_ky_primitive_dyn2.uasset
│   │   │   │       │       │   ├── M_ky_primitive.uasset
│   │   │   │       │       │   ├── M_ky_shockWave03_4x4.uasset
│   │   │   │       │       │   ├── M_ky_smoke01.uasset
│   │   │   │       │       │   ├── M_ky_storm01.uasset
│   │   │   │       │       │   ├── M_ky_stormDeco01.uasset
│   │   │   │       │       │   ├── M_ky_subUV_dynRGB.uasset
│   │   │   │       │       │   └── M_ky_thunderForBeam.uasset
│   │   │   │       │       ├── Meshes
│   │   │   │       │       │   ├── SM_ky_circleDist06.uasset
│   │   │   │       │       │   ├── SM_ky_quad_centerRot.uasset
│   │   │   │       │       │   └── SM_ky_tornado07.uasset
│   │   │   │       │       ├── Particles
│   │   │   │       │       │   ├── P_ky_darkStorm.uasset
│   │   │   │       │       │   ├── P_ky_explosion.uasset
│   │   │   │       │       │   ├── P_ky_fireBall.uasset
│   │   │   │       │       │   ├── P_ky_fireStorm.uasset
│   │   │   │       │       │   ├── P_ky_ThunderBallHit.uasset
│   │   │   │       │       │   ├── P_ky_thunderBall.uasset
│   │   │   │       │       │   └── P_ky_thunderStorm.uasset
│   │   │   │       │       └── Textures
│   │   │   │       │           ├── T_ky_bg_LC.uasset
│   │   │   │       │           ├── T_ky_deco_doom.uasset
│   │   │   │       │           ├── T_ky_decoLinesB.uasset
│   │   │   │       │           ├── T_ky_decoLines.uasset
│   │   │   │       │           ├── T_ky_dist_noise.uasset
│   │   │   │       │           ├── T_ky_flare_a.uasset
│   │   │   │       │           ├── T_ky_lightning02_4x4.uasset
│   │   │   │       │           ├── T_ky_lightningDust01_4x4.uasset
│   │   │   │       │           ├── T_ky_maskRGB3.uasset
│   │   │   │       │           ├── T_ky_noise17.uasset
│   │   │   │       │           ├── T_ky_noise3.uasset
│   │   │   │       │           ├── T_ky_noise4.uasset
│   │   │   │       │           ├── T_ky_noise5.uasset
│   │   │   │       │           ├── T_ky_noise6.uasset
│   │   │   │       │           ├── T_ky_shockWave03_4x4.uasset
│   │   │   │       │           ├── T_ky_smoke1.uasset
│   │   │   │       │           ├── T_ky_smoke2.uasset
│   │   │   │       │           └── T_ky_smoke_kai.uasset
│   │   │   │       └── Melee
│   │   │   │           ├── Axes
│   │   │   │           │   ├── Axe
│   │   │   │           │   │   ├── M_Blade_TAxe.uasset
│   │   │   │           │   │   ├── SK_Blade_TAxe_Skeleton.uasset
│   │   │   │           │   │   ├── SK_Blade_TAxe.uasset
│   │   │   │           │   │   ├── T_Blade_TAxe1_D.uasset
│   │   │   │           │   │   ├── T_Blade_TAxe1_N.uasset
│   │   │   │           │   │   ├── T_Blade_TAxe2_D.uasset
│   │   │   │           │   │   ├── T_Blade_TAxe2_M.uasset
│   │   │   │           │   │   └── T_Blade_TAxe2_N.uasset
│   │   │   │           │   ├── BP_Axe.uasset
│   │   │   │           │   └── SM_Axe.uasset
│   │   │   │           ├── BasicSword
│   │   │   │           │   ├── BP_BaseSword.uasset
│   │   │   │           │   └── SM_WP_GothicKnight_Sword.uasset
│   │   │   │           ├── Blade_Balloon
│   │   │   │           │   ├── BP_OneShotSword.uasset
│   │   │   │           │   ├── M_Blade_Balloon.uasset
│   │   │   │           │   ├── SK_Blade_Balloon_Skeleton.uasset
│   │   │   │           │   ├── SK_Blade_Balloon.uasset
│   │   │   │           │   ├── ST_BladeBalon.uasset
│   │   │   │           │   ├── T_Blade_Balloon1_D.uasset
│   │   │   │           │   ├── T_Blade_Balloon1_N.uasset
│   │   │   │           │   ├── T_Blade_Balloon2_D.uasset
│   │   │   │           │   └── T_Blade_Balloon2_N.uasset
│   │   │   │           ├── SpecialSword
│   │   │   │           │   ├── Blade_SwordA
│   │   │   │           │   │   ├── M_Blade_SwordA.uasset
│   │   │   │           │   │   ├── SK_Blade_SwordA_Skeleton.uasset
│   │   │   │           │   │   ├── SK_Blade_SwordA.uasset
│   │   │   │           │   │   ├── T_Blade_SwordA1_D.uasset
│   │   │   │           │   │   ├── T_Blade_SwordA1_M.uasset
│   │   │   │           │   │   ├── T_Blade_SwordA1_N.uasset
│   │   │   │           │   │   ├── T_Blade_SwordA2_D.uasset
│   │   │   │           │   │   ├── T_Blade_SwordA2_M.uasset
│   │   │   │           │   │   └── T_Blade_SwordA2_N.uasset
│   │   │   │           │   ├── BP_SpecialSword.uasset
│   │   │   │           │   └── SM_SpecialSword.uasset
│   │   │   │           └── Traces
│   │   │   │               ├── Materials
│   │   │   │               │   ├── M_Cloud.uasset
│   │   │   │               │   ├── M_FlowerFlare.uasset
│   │   │   │               │   ├── M_Galaxy4.uasset
│   │   │   │               │   └── M_SimpleTrail01.uasset
│   │   │   │               ├── NS_Axe.uasset
│   │   │   │               ├── NS_OneShotTrace.uasset
│   │   │   │               ├── NS_SpecialSword.uasset
│   │   │   │               ├── NS_SwordTrace.uasset
│   │   │   │               └── Textures
│   │   │   │                   ├── T_FlowerCut.uasset
│   │   │   │                   ├── T_Fraction01.uasset
│   │   │   │                   ├── T_GalaxyNoise02.uasset
│   │   │   │                   ├── T_MainTrail.uasset
│   │   │   │                   ├── T_Noise03.uasset
│   │   │   │                   ├── T_Noise04.uasset
│   │   │   │                   ├── T_Noise05.uasset
│   │   │   │                   ├── T_Noise06.uasset
│   │   │   │                   ├── T_RainbowFlare.uasset
│   │   │   │                   ├── T_Speed.uasset
│   │   │   │                   └── T_Tendrils.uasset
│   │   │   └── Sequences
│   │   │       └── MenuToGameplayTransition.uasset
│   │   └── SoundsForGame
│   │       ├── Cues
│   │       │   ├── Creature_1-21_Cue.uasset
│   │       │   ├── Draw_Weapon_Metal_1-1_Cue.uasset
│   │       │   ├── ElectricAttack_Cue.uasset
│   │       │   ├── EnrageRoar_Cue.uasset
│   │       │   ├── Fire_Burning_Loop_2_Cue.uasset
│   │       │   ├── Fire_Whoosh_2-15_Cue.uasset
│   │       │   ├── Magical_Interface_8-1_Cue.uasset
│   │       │   ├── Stab_4-1_Cue.uasset
│   │       │   ├── SwordSlash.uasset
│   │       │   └── WHSH_InsJ_Whooshing_Bamboo_01-01_Cue.uasset
│   │       └── Waves
│   │           ├── Creature_1-21.uasset
│   │           ├── Draw_Weapon_Metal_1-1.uasset
│   │           ├── ElectricAttack.uasset
│   │           ├── EnrageRoar.uasset
│   │           ├── Fire_Burning_Loop_2.uasset
│   │           ├── Fire_Whoosh_2-15.uasset
│   │           ├── Magical_Interface_8-1.uasset
│   │           ├── Stab_4-1.uasset
│   │           ├── SwordSlash.uasset
│   │           ├── WHSH_InsJ_Whooshing_Bamboo_01-01.uasset
│   │           └── WinGameMusic.uasset
│   ├── Collections
│   ├── Core
│   │   ├── BP_DungeonEnemiesHandler.uasset
│   │   ├── BP_GameplayGamemode.uasset
│   │   ├── BP_ProceduralDungeonGeneration.uasset
│   │   ├── DungeonRooms
│   │   │   ├── BossRoom
│   │   │   │   └── BP_BossRoom.uasset
│   │   │   ├── InportedPackages
│   │   │   │   ├── Assets
│   │   │   │   │   ├── BP-Candelabra-01.uasset
│   │   │   │   │   ├── BP-Candelabra-03.uasset
│   │   │   │   │   ├── BP-Candelabra-04.uasset
│   │   │   │   │   ├── BP-CandleLight-01.uasset
│   │   │   │   │   ├── BP-Chandelier-01.uasset
│   │   │   │   │   ├── SM_Bench.uasset
│   │   │   │   │   ├── SM_Chair.uasset
│   │   │   │   │   ├── SM-Pillar-01.uasset
│   │   │   │   │   ├── SM-Pillar-02.uasset
│   │   │   │   │   ├── SM-Shield-01-01.uasset
│   │   │   │   │   └── SM-Shield-01-02.uasset
│   │   │   │   ├── Cave_Ruins
│   │   │   │   │   ├── Material_Instances
│   │   │   │   │   │   ├── MI_Cave_Ruins_Arch_00.uasset
│   │   │   │   │   │   ├── MI_Cave_Ruins_Pillar_00.uasset
│   │   │   │   │   │   ├── MI_Metal_Bars.uasset
│   │   │   │   │   │   └── MI_Stone_0.uasset
│   │   │   │   │   ├── Materials
│   │   │   │   │   │   ├── M_Base2.uasset
│   │   │   │   │   │   ├── M_Base.uasset
│   │   │   │   │   │   └── M_Stone.uasset
│   │   │   │   │   ├── Meshes
│   │   │   │   │   │   ├── SM_Bars.uasset
│   │   │   │   │   │   ├── SM_Cave_Ruins_Arch_00.uasset
│   │   │   │   │   │   └── SM_Cave_Ruins_Pillar_00.uasset
│   │   │   │   │   └── Textures
│   │   │   │   │       ├── T_Bars_AO_R_MT.uasset
│   │   │   │   │       ├── T_Bars_BC.uasset
│   │   │   │   │       ├── T_Bars_N.uasset
│   │   │   │   │       ├── T_Cave_Ruins_Arch_00_AO_R_MT.uasset
│   │   │   │   │       ├── T_Cave_Ruins_Arch_00_BC.uasset
│   │   │   │   │       ├── T_Cave_Ruins_Arch_00_N.uasset
│   │   │   │   │       ├── T_Cave_Ruins_Pillar_00_AO_R_MT.uasset
│   │   │   │   │       ├── T_Cave_Ruins_Pillar_00_BC.uasset
│   │   │   │   │       ├── T_Cave_Ruins_Pillar_00_N.uasset
│   │   │   │   │       ├── T_Stone_01_AO.uasset
│   │   │   │   │       ├── T_Stone_01_BC.uasset
│   │   │   │   │       ├── T_Stone_01_M.uasset
│   │   │   │   │       ├── T_Stone_01_R.uasset
│   │   │   │   │       ├── T_Torture_Devices_Breaking_Wheel_AO_R_MT.uasset
│   │   │   │   │       ├── T_Torture_Devices_Breaking_Wheel_BC.uasset
│   │   │   │   │       └── T_Torture_Devices_Breaking_Wheel_N.uasset
│   │   │   │   ├── GDProp
│   │   │   │   │   └── Environment
│   │   │   │   │       ├── Asset
│   │   │   │   │       │   ├── Material
│   │   │   │   │       │   │   ├── MI_Cathedral_Trim_01a.uasset
│   │   │   │   │       │   │   ├── MIM_Props.uasset
│   │   │   │   │       │   │   ├── MI_Skeleton_01a.uasset
│   │   │   │   │       │   │   ├── MI_StoneDebris_01a.uasset
│   │   │   │   │       │   │   ├── MI_StoneDebris_02a.uasset
│   │   │   │   │       │   │   └── MI_Tiles_01a.uasset
│   │   │   │   │       │   ├── Mesh
│   │   │   │   │       │   │   ├── Architecture
│   │   │   │   │       │   │   │   └── Floors
│   │   │   │   │       │   │   │       └── SM_ArchFloor_01a.uasset
│   │   │   │   │       │   │   ├── Debris
│   │   │   │   │       │   │   │   ├── SM_StoneDebris_01a.uasset
│   │   │   │   │       │   │   │   └── SM_StoneDebris_02a.uasset
│   │   │   │   │       │   │   └── Props
│   │   │   │   │       │   │       ├── SM_Feet_01a.uasset
│   │   │   │   │       │   │       ├── SM_Hand_01a.uasset
│   │   │   │   │       │   │       ├── SM_Leg_01b.uasset
│   │   │   │   │       │   │       ├── SM_Ribs_01a.uasset
│   │   │   │   │       │   │       └── SM_Skull_01a.uasset
│   │   │   │   │       │   └── Texture
│   │   │   │   │       │       ├── T_Cathedral_Floor_02
│   │   │   │   │       │       │   ├── T_Cathedral_Floor_02a_D_03.uasset
│   │   │   │   │       │       │   ├── T_Cathedral_Floor_02a_H.uasset
│   │   │   │   │       │       │   ├── T_Cathedral_Floor_02a_N.uasset
│   │   │   │   │       │       │   ├── T_Cathedral_Floor_02a_ORM.uasset
│   │   │   │   │       │       │   ├── T_Cathedral_Floor_02b_D_03.uasset
│   │   │   │   │       │       │   ├── T_Cathedral_Floor_02b_H.uasset
│   │   │   │   │       │       │   ├── T_Cathedral_Floor_02b_N.uasset
│   │   │   │   │       │       │   └── T_Cathedral_Floor_02b_ORM.uasset
│   │   │   │   │       │       ├── T_Cathedral_Trim
│   │   │   │   │       │       │   ├── T_Cathedral_Trim_01a_D.uasset
│   │   │   │   │       │       │   ├── T_Cathedral_Trim_01a_H.uasset
│   │   │   │   │       │       │   ├── T_Cathedral_Trim_01a_N.uasset
│   │   │   │   │       │       │   ├── T_Cathedral_Trim_01a_ORM.uasset
│   │   │   │   │       │       │   ├── T_Cathedral_Trim_01a_TM.uasset
│   │   │   │   │       │       │   ├── T_Cathedral_Trim_01b_D.uasset
│   │   │   │   │       │       │   ├── T_Cathedral_Trim_01b_H.uasset
│   │   │   │   │       │       │   ├── T_Cathedral_Trim_01b_N.uasset
│   │   │   │   │       │       │   └── T_Cathedral_Trim_01b_ORM.uasset
│   │   │   │   │       │       ├── T_Skeleton
│   │   │   │   │       │       │   ├── T_Skeleton_01a_D.uasset
│   │   │   │   │       │       │   ├── T_Skeleton_01a_N.uasset
│   │   │   │   │       │       │   └── T_Skeleton_01a_ORM.uasset
│   │   │   │   │       │       ├── T_StoneDebris_01a
│   │   │   │   │       │       │   ├── T_StoneDebris_01a_B.uasset
│   │   │   │   │       │       │   ├── T_StoneDebris_01a_N.uasset
│   │   │   │   │       │       │   └── T_StoneDebris_01a_ORM.uasset
│   │   │   │   │       │       └── T_StoneDebris_02a
│   │   │   │   │       │           ├── T_StoneDebris_02a_B.uasset
│   │   │   │   │       │           ├── T_StoneDebris_02a_N.uasset
│   │   │   │   │       │           └── T_StoneDebris_02a_ORM.uasset
│   │   │   │   │       └── MasterMaterial
│   │   │   │   │           ├── Material
│   │   │   │   │           │   └── MM_MaterMaterial.uasset
│   │   │   │   │           ├── Material_Function
│   │   │   │   │           │   ├── MF_AODirt.uasset
│   │   │   │   │           │   ├── MF_FourNormalCombine.uasset
│   │   │   │   │           │   ├── MF_FuzzyMasterlayer.uasset
│   │   │   │   │           │   ├── MF_HeightExtracted.uasset
│   │   │   │   │           │   ├── MF_MacroAlbedo.uasset
│   │   │   │   │           │   ├── MF_MacroNormal.uasset
│   │   │   │   │           │   ├── MF_Masterlayer.uasset
│   │   │   │   │           │   ├── MF_MatLayerBlend.uasset
│   │   │   │   │           │   ├── MF_RippleS.uasset
│   │   │   │   │           │   ├── MF_Ripple.uasset
│   │   │   │   │           │   ├── MF_ScaleBaseTile.uasset
│   │   │   │   │           │   ├── MF_Upvector.uasset
│   │   │   │   │           │   ├── MF_Vertexpaint.uasset
│   │   │   │   │           │   ├── MF_Wetness.uasset
│   │   │   │   │           │   └── MF_WorldAlignedNormal.uasset
│   │   │   │   │           └── Texture
│   │   │   │   │               ├── T_Grunge
│   │   │   │   │               │   ├── T_Grunge_02a.uasset
│   │   │   │   │               │   └── T_Grunge_03a.uasset
│   │   │   │   │               ├── T_Height_H.uasset
│   │   │   │   │               ├── T_Mask_ORM.uasset
│   │   │   │   │               ├── T_rain_ripples.uasset
│   │   │   │   │               ├── T_TintMask_01_TM.uasset
│   │   │   │   │               ├── T_TintMask_02_TM.uasset
│   │   │   │   │               └── T_Water_N.uasset
│   │   │   │   ├── Kobo_Dungeon
│   │   │   │   │   ├── Blueprints
│   │   │   │   │   │   ├── BP-Brazier-01.uasset
│   │   │   │   │   │   ├── BP-Brazier-02.uasset
│   │   │   │   │   │   ├── BP-Brazier-03.uasset
│   │   │   │   │   │   ├── BP-CandleLight-01.uasset
│   │   │   │   │   │   ├── BP-CandleLight-02.uasset
│   │   │   │   │   │   ├── BP-CandleLight-03.uasset
│   │   │   │   │   │   ├── BP-CandleLight-04.uasset
│   │   │   │   │   │   ├── BP-CandleLight-05.uasset
│   │   │   │   │   │   ├── BP-CandleLight-06.uasset
│   │   │   │   │   │   └── DoorMesh.uasset
│   │   │   │   │   ├── FX
│   │   │   │   │   │   ├── FX-BrazierEmbers-01.uasset
│   │   │   │   │   │   └── FX-BrazierEmbers-02.uasset
│   │   │   │   │   ├── Materials
│   │   │   │   │   │   ├── M-FX
│   │   │   │   │   │   │   ├── M-CandleFlame.uasset
│   │   │   │   │   │   │   ├── M-Embers.uasset
│   │   │   │   │   │   │   ├── MI-CandleFlame-01.uasset
│   │   │   │   │   │   │   ├── MI-CandleFlame-02.uasset
│   │   │   │   │   │   │   ├── MI-CandleFlame-03.uasset
│   │   │   │   │   │   │   ├── MI-CandleFlame-04.uasset
│   │   │   │   │   │   │   └── MI-CandleFlame-05.uasset
│   │   │   │   │   │   ├── M-Instance
│   │   │   │   │   │   │   ├── MI-Brazier-01-01.uasset
│   │   │   │   │   │   │   ├── MI-Brazier-01-02.uasset
│   │   │   │   │   │   │   ├── MI-Brazier-02-01.uasset
│   │   │   │   │   │   │   ├── MI-Brazier-02-02.uasset
│   │   │   │   │   │   │   ├── MI-Candelabra-01.uasset
│   │   │   │   │   │   │   ├── MI-Candelabra-03-01.uasset
│   │   │   │   │   │   │   ├── MI-Candelabra-03-02.uasset
│   │   │   │   │   │   │   ├── MI-Candelabra-04-01.uasset
│   │   │   │   │   │   │   ├── MI-Candelabra-04-02.uasset
│   │   │   │   │   │   │   ├── MI-Candle-01.uasset
│   │   │   │   │   │   │   ├── MI-Chandelier-01-01.uasset
│   │   │   │   │   │   │   ├── MI-Chandelier-01-02.uasset
│   │   │   │   │   │   │   ├── MI-Chandelier-01-03.uasset
│   │   │   │   │   │   │   ├── MI-Gate-01-01.uasset
│   │   │   │   │   │   │   ├── MI-Gate-01-02.uasset
│   │   │   │   │   │   │   ├── MI-Pillar-01.uasset
│   │   │   │   │   │   │   ├── MI-Pillar-02.uasset
│   │   │   │   │   │   │   ├── MI-Shield-01-01.uasset
│   │   │   │   │   │   │   ├── MI-Shield-01-02.uasset
│   │   │   │   │   │   │   ├── MI-Shield-01-03.uasset
│   │   │   │   │   │   │   ├── MI-Wall-01-01.uasset
│   │   │   │   │   │   │   ├── MI-Wall-01-02.uasset
│   │   │   │   │   │   │   ├── MI-Wall-02-01.uasset
│   │   │   │   │   │   │   ├── MI-Wall-02-02.uasset
│   │   │   │   │   │   │   └── MI-Wall-03.uasset
│   │   │   │   │   │   ├── M-LightFunction
│   │   │   │   │   │   │   ├── MI-LightFlicker-04.uasset
│   │   │   │   │   │   │   ├── MI-LightFlicker-05.uasset
│   │   │   │   │   │   │   └── M-LightFlicker.uasset
│   │   │   │   │   │   └── M-Master
│   │   │   │   │   │       └── M-Master.uasset
│   │   │   │   │   ├── Meshes
│   │   │   │   │   │   ├── SM-Brazier-01-01.uasset
│   │   │   │   │   │   ├── SM-Brazier-01-02.uasset
│   │   │   │   │   │   ├── SM-Brazier-02-01.uasset
│   │   │   │   │   │   ├── SM-Brazier-02-02.uasset
│   │   │   │   │   │   ├── SM-Candelabra-01.uasset
│   │   │   │   │   │   ├── SM-Candelabra-03.uasset
│   │   │   │   │   │   ├── SM-Candelabra-04.uasset
│   │   │   │   │   │   ├── SM-Candle-01.uasset
│   │   │   │   │   │   ├── SM-CandleFlame-01.uasset
│   │   │   │   │   │   ├── SM-Chandelier-01-01.uasset
│   │   │   │   │   │   ├── SM-Chandelier-01-02.uasset
│   │   │   │   │   │   ├── SM-Gate-01-01.uasset
│   │   │   │   │   │   ├── SM-Gate-01-02.uasset
│   │   │   │   │   │   ├── SM-Wall-01-01.uasset
│   │   │   │   │   │   ├── SM-Wall-01-02.uasset
│   │   │   │   │   │   ├── SM-Wall-02-01.uasset
│   │   │   │   │   │   ├── SM-Wall-02-02.uasset
│   │   │   │   │   │   └── SM-Wall-03.uasset
│   │   │   │   │   └── Textures
│   │   │   │   │       ├── A-Blank-01.uasset
│   │   │   │   │       ├── N-Blank-01.uasset
│   │   │   │   │       ├── T-Albedo
│   │   │   │   │       │   ├── A-Brazier-01-01.uasset
│   │   │   │   │       │   ├── A-Brazier-01-02.uasset
│   │   │   │   │       │   ├── A-Brazier-02-01.uasset
│   │   │   │   │       │   ├── A-Brazier-02-02.uasset
│   │   │   │   │       │   ├── A-Candelabra-01.uasset
│   │   │   │   │       │   ├── A-Candelabra-03-01.uasset
│   │   │   │   │       │   ├── A-Candelabra-03-02.uasset
│   │   │   │   │       │   ├── A-Candelabra-04-01.uasset
│   │   │   │   │       │   ├── A-Candelabra-04-02.uasset
│   │   │   │   │       │   ├── A-Candle-01.uasset
│   │   │   │   │       │   ├── A-Chandelier-01-01.uasset
│   │   │   │   │       │   ├── A-Chandelier-01-02.uasset
│   │   │   │   │       │   ├── A-Chandelier-01-03.uasset
│   │   │   │   │       │   ├── A-Gate-01-01.uasset
│   │   │   │   │       │   ├── A-Gate-01-02.uasset
│   │   │   │   │       │   ├── A-Pillar-01.uasset
│   │   │   │   │       │   ├── A-Pillar-02.uasset
│   │   │   │   │       │   ├── A-Shield-01-01.uasset
│   │   │   │   │       │   ├── A-Shield-01-02.uasset
│   │   │   │   │       │   ├── A-Shield-01-03.uasset
│   │   │   │   │       │   ├── A-Wall-01-01.uasset
│   │   │   │   │       │   ├── A-Wall-01-02.uasset
│   │   │   │   │       │   ├── A-Wall-02-01.uasset
│   │   │   │   │       │   ├── A-Wall-02-02.uasset
│   │   │   │   │       │   └── A-Wall-03.uasset
│   │   │   │   │       ├── T-FX
│   │   │   │   │       │   ├── A-CandleFlame.uasset
│   │   │   │   │       │   └── N-CandleFlame.uasset
│   │   │   │   │       └── T-Normal
│   │   │   │   │           ├── N-Brazier-01-01.uasset
│   │   │   │   │           ├── N-Brazier-01-02.uasset
│   │   │   │   │           ├── N-Brazier-02-01.uasset
│   │   │   │   │           ├── N-Brazier-02-02.uasset
│   │   │   │   │           ├── N-Candelabra-01.uasset
│   │   │   │   │           ├── N-Candelabra-03-01.uasset
│   │   │   │   │           ├── N-Candelabra-03-02.uasset
│   │   │   │   │           ├── N-Candelabra-04-01.uasset
│   │   │   │   │           ├── N-Candelabra-04-02.uasset
│   │   │   │   │           ├── N-Candle-01.uasset
│   │   │   │   │           ├── N-Chandelier-01-01.uasset
│   │   │   │   │           ├── N-Chandelier-01-02.uasset
│   │   │   │   │           ├── N-Chandelier-01-03.uasset
│   │   │   │   │           ├── N-Gate-01-01.uasset
│   │   │   │   │           ├── N-Gate-01-02.uasset
│   │   │   │   │           ├── N-Pillar-01.uasset
│   │   │   │   │           ├── N-Pillar-02.uasset
│   │   │   │   │           ├── N-Shield-01-01.uasset
│   │   │   │   │           ├── N-Shield-01-02.uasset
│   │   │   │   │           ├── N-Shield-01-03.uasset
│   │   │   │   │           ├── N-Wall-01-01.uasset
│   │   │   │   │           ├── N-Wall-01-02.uasset
│   │   │   │   │           ├── N-Wall-02-01.uasset
│   │   │   │   │           ├── N-Wall-02-02.uasset
│   │   │   │   │           └── N-Wall-03.uasset
│   │   │   │   ├── Music
│   │   │   │   │   ├── Last_Sound_in_the_Dust_Loop_Cue.uasset
│   │   │   │   │   ├── Last_Sound_in_the_Dust_Loop.uasset
│   │   │   │   │   ├── SCM_Master.uasset
│   │   │   │   │   ├── Surrounded_by_Darkness_Loop_Cue.uasset
│   │   │   │   │   ├── Surrounded_by_Darkness_Loop.uasset
│   │   │   │   │   ├── The_Kingdom_Beyond_loop_Cue.uasset
│   │   │   │   │   └── The_Kingdom_Beyond_loop.uasset
│   │   │   │   ├── NUProp
│   │   │   │   │   ├── materials
│   │   │   │   │   │   └── floor
│   │   │   │   │   │       ├── masters
│   │   │   │   │   │       │   └── m_diamond_pattern.uasset
│   │   │   │   │   │       ├── m_BigWalls1.uasset
│   │   │   │   │   │       ├── m_big_walls2.uasset
│   │   │   │   │   │       ├── m_bigWalls3.uasset
│   │   │   │   │   │       └── m_bigWalls4.uasset
│   │   │   │   │   └── textures
│   │   │   │   │       ├── common
│   │   │   │   │       │   ├── t_noise_01_n.uasset
│   │   │   │   │       │   └── t_roughness_01_m.uasset
│   │   │   │   │       └── floor
│   │   │   │   │           └── t_rubbermat_01
│   │   │   │   │               ├── t_rubbermat_01_ao.uasset
│   │   │   │   │               ├── t_rubbermat_01_d.uasset
│   │   │   │   │               └── t_rubbermat_01_n.uasset
│   │   │   │   ├── TemplesOfCambodia
│   │   │   │   │   ├── BaseMaterials
│   │   │   │   │   │   ├── m_BaseMaterial_01_01.uasset
│   │   │   │   │   │   ├── m_BaseMaterial_01_02_Tile.uasset
│   │   │   │   │   │   ├── PhysicalMaterials
│   │   │   │   │   │   │   └── PM_Rock_01_01.uasset
│   │   │   │   │   │   └── Textures
│   │   │   │   │   │       ├── t_baseColor_01_01.uasset
│   │   │   │   │   │       ├── t_baseNormalMap_01_01.uasset
│   │   │   │   │   │       ├── t_Detail_01_01_n.uasset
│   │   │   │   │   │       ├── t_Detail_01_01_r.uasset
│   │   │   │   │   │       ├── t_Detail_01_11_n.uasset
│   │   │   │   │   │       ├── t_Detail_01_11_r.uasset
│   │   │   │   │   │       ├── t_GreyScaleLinear_01_01.uasset
│   │   │   │   │   │       ├── t_Masks_01_01.uasset
│   │   │   │   │   │       └── t_Noise_01_01_n.uasset
│   │   │   │   │   └── Environment
│   │   │   │   │       ├── BigRock_01
│   │   │   │   │       │   ├── mi_BigRock_01_00.uasset
│   │   │   │   │       │   ├── mi_BigRock_01_01.uasset
│   │   │   │   │       │   ├── mi_BigRock_01_02.uasset
│   │   │   │   │       │   ├── mi_BigRock_01_03.uasset
│   │   │   │   │       │   ├── mi_BigRock_01_04.uasset
│   │   │   │   │       │   ├── mi_BigRock_01_05.uasset
│   │   │   │   │       │   ├── mi_BigRock_01_06.uasset
│   │   │   │   │       │   ├── mi_BigRock_01_07.uasset
│   │   │   │   │       │   ├── sm_BigRock_01_01.uasset
│   │   │   │   │       │   ├── sm_BigRock_01_02.uasset
│   │   │   │   │       │   ├── t_BigRock_01_01_bc.uasset
│   │   │   │   │       │   ├── t_BigRock_01_01_n.uasset
│   │   │   │   │       │   ├── t_BigRock_01_02_bc.uasset
│   │   │   │   │       │   ├── t_BigRock_01_02_n.uasset
│   │   │   │   │       │   ├── t_BigRock_01_03_bc.uasset
│   │   │   │   │       │   ├── t_BigRock_01_03_n.uasset
│   │   │   │   │       │   ├── t_BigRock_01_04_bc.uasset
│   │   │   │   │       │   ├── t_BigRock_01_04_n.uasset
│   │   │   │   │       │   ├── t_BigRock_01_05_bc.uasset
│   │   │   │   │       │   ├── t_BigRock_01_05_n.uasset
│   │   │   │   │       │   ├── t_BigRock_01_06_bc.uasset
│   │   │   │   │       │   ├── t_BigRock_01_06_n.uasset
│   │   │   │   │       │   ├── t_BigRock_01_07_bc.uasset
│   │   │   │   │       │   └── t_BigRock_01_07_n.uasset
│   │   │   │   │       ├── BigRock_02
│   │   │   │   │       │   ├── mi_BigRock_02_00.uasset
│   │   │   │   │       │   ├── mi_BigRock_02_01.uasset
│   │   │   │   │       │   ├── mi_BigRock_02_02.uasset
│   │   │   │   │       │   ├── mi_BigRock_02_03.uasset
│   │   │   │   │       │   ├── mi_BigRock_02_04.uasset
│   │   │   │   │       │   ├── sm_BigRock_02_01.uasset
│   │   │   │   │       │   ├── t_BigRock_02_01_bc.uasset
│   │   │   │   │       │   ├── t_BigRock_02_01_n.uasset
│   │   │   │   │       │   ├── t_BigRock_02_02_bc.uasset
│   │   │   │   │       │   ├── t_BigRock_02_02_n.uasset
│   │   │   │   │       │   ├── t_BigRock_02_03_bc.uasset
│   │   │   │   │       │   ├── t_BigRock_02_03_n.uasset
│   │   │   │   │       │   ├── t_BigRock_02_04_bc.uasset
│   │   │   │   │       │   └── t_BigRock_02_04_n.uasset
│   │   │   │   │       ├── BigRock_03
│   │   │   │   │       │   ├── mi_BigRock_03_00.uasset
│   │   │   │   │       │   ├── mi_BigRock_03_01.uasset
│   │   │   │   │       │   ├── mi_BigRock_03_02.uasset
│   │   │   │   │       │   ├── mi_BigRock_03_03.uasset
│   │   │   │   │       │   ├── mi_BigRock_03_04.uasset
│   │   │   │   │       │   ├── mi_BigRock_03_05.uasset
│   │   │   │   │       │   ├── sm_BigRock_03_01.uasset
│   │   │   │   │       │   ├── t_BigRock_03_01_bc.uasset
│   │   │   │   │       │   ├── t_BigRock_03_01_n.uasset
│   │   │   │   │       │   ├── t_BigRock_03_02_bc.uasset
│   │   │   │   │       │   ├── t_BigRock_03_02_n.uasset
│   │   │   │   │       │   ├── t_BigRock_03_03_bc.uasset
│   │   │   │   │       │   ├── t_BigRock_03_03_n.uasset
│   │   │   │   │       │   ├── t_BigRock_03_04_bc.uasset
│   │   │   │   │       │   ├── t_BigRock_03_04_n.uasset
│   │   │   │   │       │   ├── t_BigRock_03_05_bc.uasset
│   │   │   │   │       │   └── t_BigRock_03_05_n.uasset
│   │   │   │   │       ├── BigRock_04
│   │   │   │   │       │   ├── mi_BigRock_04_00.uasset
│   │   │   │   │       │   ├── mi_BigRock_04_01.uasset
│   │   │   │   │       │   ├── mi_BigRock_04_02.uasset
│   │   │   │   │       │   ├── mi_BigRock_04_03.uasset
│   │   │   │   │       │   ├── mi_BigRock_04_04.uasset
│   │   │   │   │       │   ├── sm_BigRock_04_04.uasset
│   │   │   │   │       │   ├── t_BigRock_04_01_bc.uasset
│   │   │   │   │       │   ├── t_BigRock_04_01_n.uasset
│   │   │   │   │       │   ├── t_BigRock_04_02_bc.uasset
│   │   │   │   │       │   ├── t_BigRock_04_02_n.uasset
│   │   │   │   │       │   ├── t_BigRock_04_03_bc.uasset
│   │   │   │   │       │   ├── t_BigRock_04_03_n.uasset
│   │   │   │   │       │   ├── t_BigRock_04_04_bc.uasset
│   │   │   │   │       │   └── t_BigRock_04_04_n.uasset
│   │   │   │   │       ├── PathRocky_01
│   │   │   │   │       │   ├── mi_PathRocky_01_01.uasset
│   │   │   │   │       │   ├── mi_PathRocky_01_02.uasset
│   │   │   │   │       │   ├── mi_PathRocky_01_03.uasset
│   │   │   │   │       │   ├── mi_PathRocky_01_04.uasset
│   │   │   │   │       │   ├── sm_PathRocky_01_01.uasset
│   │   │   │   │       │   ├── t_PathRocky_01_01_bc.uasset
│   │   │   │   │       │   ├── t_PathRocky_01_01_n.uasset
│   │   │   │   │       │   ├── t_PathRocky_01_02_bc.uasset
│   │   │   │   │       │   ├── t_PathRocky_01_02_n.uasset
│   │   │   │   │       │   ├── t_PathRocky_01_03_bc.uasset
│   │   │   │   │       │   ├── t_PathRocky_01_03_n.uasset
│   │   │   │   │       │   ├── t_PathRocky_01_04_bc.uasset
│   │   │   │   │       │   └── t_PathRocky_01_04_n.uasset
│   │   │   │   │       └── TileGround_01
│   │   │   │   │           ├── mi_TileGround_01_01.uasset
│   │   │   │   │           ├── sm_TileGround_01_01.uasset
│   │   │   │   │           ├── t_TileGround_01_01_bc.uasset
│   │   │   │   │           └── t_TileGround_01_01_n.uasset
│   │   │   │   └── Weapon_Pack
│   │   │   │       ├── Materials
│   │   │   │       │   └── Props
│   │   │   │       │       └── Interior
│   │   │   │       │           ├── M_Props2.uasset
│   │   │   │       │           └── M_Props3.uasset
│   │   │   │       └── Textures
│   │   │   │           └── Props
│   │   │   │               └── Interior
│   │   │   │                   ├── T_Props2_BaseColor.uasset
│   │   │   │                   ├── T_Props2_Normal.uasset
│   │   │   │                   ├── T_Props2_OcclusionRoughnessMetallic.uasset
│   │   │   │                   ├── T_Prop_Set3_BaseColor.uasset
│   │   │   │                   ├── T_Prop_Set3_Normal.uasset
│   │   │   │                   └── T_Prop_Set3_OcclusionRoughnessMetallic.uasset
│   │   │   ├── SpecialRooms
│   │   │   │   ├── BP_SpecialRoom1.uasset
│   │   │   │   ├── BP_SpecialRoom2.uasset
│   │   │   │   ├── BP_SpecialRoom3.uasset
│   │   │   │   └── BP_SpecialRoom4.uasset
│   │   │   └── Starting_BasicRooms
│   │   │       ├── BP_BasicRoom1.uasset
│   │   │       ├── BP_BasicRoom2.uasset
│   │   │       ├── BP_BasicRoom3.uasset
│   │   │       ├── BP_BasicRoom4.uasset
│   │   │       ├── BP_BasicRoom5.uasset
│   │   │       ├── BP_BasicRoom6.uasset
│   │   │       └── BP_StartingRoom.uasset
│   │   └── UI
│   │       ├── PersonalizeDecals
│   │       │   ├── M_DecalsMaster.uasset
│   │       │   ├── MI_Bravehearth.uasset
│   │       │   ├── MI_ChoosePath.uasset
│   │       │   ├── MI_DungeonFIghter.uasset
│   │       │   └── MI_TimidSteps.uasset
│   │       ├── Textures
│   │       │   ├── Braveheart.uasset
│   │       │   ├── ChooseFathePng.uasset
│   │       │   ├── DungeonFighterPortraint.uasset
│   │       │   └── TimidsSteps.uasset
│   │       └── WidgetsMenu
│   │           ├── Fonts
│   │           │   ├── DistilieryFontDataTable.uasset
│   │           │   ├── Distillery_Strong_Font.uasset
│   │           │   └── Distillery_Strong.uasset
│   │           ├── UITextures
│   │           │   ├── ArrowLeft.uasset
│   │           │   ├── ArrowRights.uasset
│   │           │   ├── BackBtn.uasset
│   │           │   ├── Captura_de_pantalla_2024-12-17_193816.uasset
│   │           │   ├── DisplayTextImage.uasset
│   │           │   ├── NoTextBttn.uasset
│   │           │   ├── PlayBtn.uasset
│   │           │   ├── QuitBtn.uasset
│   │           │   ├── SettingsBackground.uasset
│   │           │   └── SettingsBtn.uasset
│   │           ├── WBP_CinematicWidget.uasset
│   │           ├── WBP_CustomMenu.uasset
│   │           ├── WBP_MainMenuWidget.uasset
│   │           ├── WBP_PauseMenu.uasset
│   │           └── WBP_SelectionBase.uasset
│   ├── Developers
│   │   ├── tinch
│   │   │   └── Collections
│   │   └── Tincho
│   │       └── Collections
│   ├── Fab
│   │   └── Megascans
│   │       └── Decals
│   │           ├── Blood_Stain_shenedvc
│   │           │   └── Low
│   │           │       ├── MI_shenedvc.uasset
│   │           │       ├── T_shenedvc_1K_B-O.uasset
│   │           │       ├── T_shenedvc_1K_N.uasset
│   │           │       └── T_shenedvc_1K_ORM.uasset
│   │           ├── Hand_Smear_se0wefxp
│   │           │   └── Low
│   │           │       ├── MI_se0wefxp.uasset
│   │           │       ├── T_se0wefxp_1K_B-O.uasset
│   │           │       ├── T_se0wefxp_1K_N.uasset
│   │           │       └── T_se0wefxp_1K_ORM.uasset
│   │           ├── High_Velocity_Blood_Spatter_sfcsbflp
│   │           │   └── Low
│   │           │       ├── MI_sfcsbflp.uasset
│   │           │       ├── T_sfcsbflp_1K_B-O.uasset
│   │           │       ├── T_sfcsbflp_1K_N.uasset
│   │           │       └── T_sfcsbflp_1K_ORM.uasset
│   │           └── PersonalizeDecals
│   │               ├── ChoosePathMaterial.uasset
│   │               ├── M_DecalsMaster.uasset
│   │               ├── MI_Bravehearth.uasset
│   │               └── MI_TimidSteps.uasset
│   ├── Maps
│   │   ├── _GENERATED
│   │   │   └── Tincho
│   │   │       ├── Box_DDA24B09.uasset
│   │   │       └── Sphere_BC193DA0.uasset
│   │   ├── M_MainLevel.umap
│   │   ├── M_MainMenu-Tutorial_BuiltData.uasset
│   │   ├── M_MainMenu-Tutorial.umap
│   │   ├── TestMap_BuiltData.uasset
│   │   └── TestMap.umap
│   └── MSPresets
│       ├── M_MS_Billboard_Material
│       │   └── M_MS_Billboard_Material.uasset
│       ├── M_MS_Decal_Material
│       │   ├── MF_QuixelDecalPOM.uasset
│       │   └── M_MS_Decal_Material.uasset
│       ├── M_MS_Decal_Material_VT
│       │   ├── MF_QuixelDecalPOM.uasset
│       │   └── M_MS_Decal_Material_VT.uasset
│       ├── M_MS_Default_Fuzz_Material
│       │   ├── Functions
│       │   │   ├── MF_Fuzz.uasset
│       │   │   └── MF_Tiling.uasset
│       │   └── M_MS_Default_Fuzz_Material.uasset
│       ├── M_MS_Default_Fuzz_Material_VT
│       │   ├── Functions
│       │   │   ├── MF_Fuzz.uasset
│       │   │   └── MF_Tiling.uasset
│       │   └── M_MS_Default_Fuzz_Material_VT.uasset
│       ├── M_MS_Default_Material
│       │   ├── Functions
│       │   │   ├── MF_DetailNormalTiling.uasset
│       │   │   ├── MF_Displacement.uasset
│       │   │   ├── MF_Fuzz.uasset
│       │   │   ├── MF_MapAdjustments.uasset
│       │   │   ├── MF_ObjAdjustments.uasset
│       │   │   ├── MF_Tiling.uasset
│       │   │   └── MF_Transmission.uasset
│       │   └── M_MS_Default_Material.uasset
│       ├── M_MS_Default_Material_VT
│       │   ├── Functions
│       │   │   ├── MF_DetailNormalTiling.uasset
│       │   │   ├── MF_Displacement.uasset
│       │   │   ├── MF_Fuzz.uasset
│       │   │   ├── MF_MapAdjustments.uasset
│       │   │   ├── MF_ObjAdjustments.uasset
│       │   │   ├── MF_Tiling.uasset
│       │   │   └── MF_Transmission.uasset
│       │   └── M_MS_Default_Material_VT.uasset
│       ├── M_MS_Default_Transmission_Material
│       │   ├── Functions
│       │   │   └── MF_SSSObjAdjustments.uasset
│       │   └── M_MS_Default_Transmission_Material.uasset
│       ├── M_MS_Default_Transmission_Material_VT
│       │   ├── Functions
│       │   │   └── MF_SSSObjAdjustments.uasset
│       │   └── M_MS_Default_Transmission_Material_VT.uasset
│       ├── M_MS_Foliage_Material
│       │   ├── Functions
│       │   │   └── MF_Translucency.uasset
│       │   ├── MF_Translucency.uasset
│       │   └── M_MS_Foliage_Material.uasset
│       ├── M_MS_Glass_Material
│       │   ├── Functions
│       │   │   ├── MF_FrameBlend.uasset
│       │   │   ├── MF_FrameTextures.uasset
│       │   │   ├── MF_Imperfection.uasset
│       │   │   ├── MF_Refraction.uasset
│       │   │   ├── MF_TranslucencyEmission.uasset
│       │   │   ├── MF_TranslucencyMetallic.uasset
│       │   │   ├── MF_WindowImperfection.uasset
│       │   │   └── MF_WindowNormalStrength.uasset
│       │   ├── MI_MS_Glass_Material_Inst.uasset
│       │   ├── M_MS_Glass_Material.uasset
│       │   └── Textures
│       │       ├── Black.uasset
│       │       ├── FlatNormal.uasset
│       │       └── White.uasset
│       ├── M_MS_ImperfectionDecal_Material
│       │   └── M_MS_ImperfectionDecal_Material.uasset
│       ├── M_MS_ImperfectionDecal_Material_VT
│       │   └── M_MS_ImperfectionDecal_Material_VT.uasset
│       ├── M_MS_Imperfection_Material
│       │   ├── M_MS_Imperfection_Material.uasset
│       │   └── M_MS_Imperfection_Material_Var.uasset
│       ├── M_MS_Imperfection_Material_Var
│       │   └── M_MS_Imperfection_Material_Var.uasset
│       ├── M_MS_Imperfection_Material_VT
│       │   ├── M_MS_Imperfection_Material_Var_VT.uasset
│       │   └── M_MS_Imperfection_Material_VT.uasset
│       ├── M_MS_SurfaceBlend_Material
│       │   ├── LayerFunctions
│       │   │   ├── Base
│       │   │   │   ├── MF_BaseLayerAdjustments.uasset
│       │   │   │   ├── MF_BaseLayerTessellation.uasset
│       │   │   │   └── MF_BaseLayerTextures.uasset
│       │   │   ├── MF_BlendScatter.uasset
│       │   │   ├── MF_DisplacementBlend.uasset
│       │   │   ├── MF_Displacement.uasset
│       │   │   ├── MF_MaterialBlend.uasset
│       │   │   ├── MF_NormalCorrection.uasset
│       │   │   ├── MF_ScatterLayer.uasset
│       │   │   ├── Middle
│       │   │   │   ├── MF_MiddleLayerAdjustments.uasset
│       │   │   │   ├── MF_MiddleLayerTessellation.uasset
│       │   │   │   └── MF_MiddleLayerTextures.uasset
│       │   │   ├── Puddle
│       │   │   │   └── MF_PuddleLayer.uasset
│       │   │   └── Top
│       │   │       ├── MF_TopLayerAdjustments.uasset
│       │   │       ├── MF_TopLayerTessellation.uasset
│       │   │       └── MF_TopLayerTextures.uasset
│       │   └── M_MS_SurfaceBlend_Material.uasset
│       ├── M_MS_Surface_Material
│       │   ├── Functions
│       │   │   ├── MF_Displacement.uasset
│       │   │   ├── MF_MapAdjustments.uasset
│       │   │   ├── MF_ObjAdjustments.uasset
│       │   │   ├── MF_Tiling.uasset
│       │   │   └── MF_Transmission.uasset
│       │   └── M_MS_Surface_Material.uasset
│       ├── M_MS_Surface_Material_VT
│       │   ├── Functions
│       │   │   ├── MF_Displacement.uasset
│       │   │   ├── MF_MapAdjustments.uasset
│       │   │   ├── MF_ObjAdjustments.uasset
│       │   │   ├── MF_Tiling.uasset
│       │   │   └── MF_Transmission.uasset
│       │   └── M_MS_Surface_Material_VT.uasset
│       ├── MSTextures
│       │   ├── BlackPlaceholder_Color.uasset
│       │   ├── BlackPlaceholder.uasset
│       │   ├── Black.uasset
│       │   ├── FlatNormal.uasset
│       │   ├── Placeholder_Normal.uasset
│       │   ├── Placeholder.uasset
│       │   ├── WhitePlaceholder.uasset
│       │   └── White.uasset
│       └── MSVTTextures
│           ├── BlackPlaceholder.uasset
│           ├── DefaultDiffuse.uasset
│           ├── Placeholder_Normal.uasset
│           └── WhitePlaceholder.uasset
├── documentation
│   └── refactoring
│       ├── effective_mappings_by_lote.json
│       └── medieval-to-cyberpunk-refactor-plan-2025-11-16.md
├── DungeonFighter.png
├── DungeonFighter.sln
├── DungeonFighter.sln.DotSettings.user
├── DungeonFighter.uproject
├── enemies_tree.txt
├── FASE_A_INVENTARIO_ASSETS.md
├── INFORME_CIERRE_REFACTOR.md
├── INSTRUCCIONES_EJECUCION_MANUAL.md
├── NOTE_CLAUDE_USAGE.md
├── pcg_apply_replacements.py
├── PLAN_APROBADO_SCOPE_REDUCIDO.md
├── replacements.json
├── scripts
│   ├── unreal_rename_lote1_texturas.py
│   └── unreal_rename_lote2_audio.py
├── Source
│   ├── DungeonFighter
│   │   ├── Characters
│   │   │   ├── Enemies
│   │   │   │   ├── BigMeteorAttack.cpp
│   │   │   │   ├── BigMeteorAttack.h
│   │   │   │   ├── BossEnemyClass.cpp
│   │   │   │   ├── BossEnemyClass.h
│   │   │   │   ├── BossRockProjectile.cpp
│   │   │   │   ├── BossRockProjectile.h
│   │   │   │   ├── BowlingMeteorProjectile.cpp
│   │   │   │   ├── BowlingMeteorProjectile.h
│   │   │   │   ├── EnemyHealthBar.cpp
│   │   │   │   ├── EnemyHealthBar.h
│   │   │   │   ├── EnemyItemDropClass.cpp
│   │   │   │   ├── EnemyItemDropClass.h
│   │   │   │   ├── IA
│   │   │   │   │   ├── BaseEnemyIAController.cpp
│   │   │   │   │   ├── BaseEnemyIAController.h
│   │   │   │   │   ├── Services
│   │   │   │   │   │   ├── BTS_BossDistanceCalculation.cpp
│   │   │   │   │   │   ├── BTS_BossDistanceCalculation.h
│   │   │   │   │   │   ├── BTSDistanceCalculation.cpp
│   │   │   │   │   │   └── BTSDistanceCalculation.h
│   │   │   │   │   └── Tasks
│   │   │   │   │       ├── BTTask_BossJumpAttack.cpp
│   │   │   │   │       ├── BTTask_BossJumpAttack.h
│   │   │   │   │       ├── BTTask_JumpAttackSpecialEnemy.cpp
│   │   │   │   │       ├── BTTask_JumpAttackSpecialEnemy.h
│   │   │   │   │       ├── BTTaskNode_BasicEnemyAttack.cpp
│   │   │   │   │       ├── BTTaskNode_BasicEnemyAttack.h
│   │   │   │   │       ├── BTTask_PickUpRock.cpp
│   │   │   │   │       ├── BTTask_PickUpRock.h
│   │   │   │   │       ├── BTTask_ThrowRock.cpp
│   │   │   │   │       ├── BTTask_ThrowRock.h
│   │   │   │   │       ├── PerformComboAttack.cpp
│   │   │   │   │       └── PerformComboAttack.h
│   │   │   │   ├── MasterEnemyCharacter.cpp
│   │   │   │   ├── MasterEnemyCharacter.h
│   │   │   │   ├── SpecialEnemy.cpp
│   │   │   │   └── SpecialEnemy.h
│   │   │   └── Player
│   │   │       ├── PlayerCharacterClass.cpp
│   │   │       ├── PlayerCharacterClass.h
│   │   │       ├── PlayerInteractionComponent.cpp
│   │   │       ├── PlayerInteractionComponent.h
│   │   │       ├── PlayerInteractionInterface.cpp
│   │   │       ├── PlayerInteractionInterface.h
│   │   │       ├── UI
│   │   │       │   ├── MenuUI
│   │   │       │   │   ├── CustomMenu.cpp
│   │   │       │   │   ├── CustomMenu.h
│   │   │       │   │   ├── FramerateEnum.cpp
│   │   │       │   │   ├── FramerateEnum.h
│   │   │       │   │   ├── MainMenuWidget.cpp
│   │   │       │   │   ├── MainMenuWidget.h
│   │   │       │   │   ├── PauseMenuWidget.cpp
│   │   │       │   │   ├── PauseMenuWidget.h
│   │   │       │   │   ├── SelectionBase.cpp
│   │   │       │   │   ├── SelectionBase.h
│   │   │       │   │   ├── SelectOption.cpp
│   │   │       │   │   ├── SelectOption.h
│   │   │       │   │   ├── SettingsMenu.cpp
│   │   │       │   │   └── SettingsMenu.h
│   │   │       │   ├── PlayerGameplayUIClass.cpp
│   │   │       │   ├── PlayerGameplayUIClass.h
│   │   │       │   ├── PlayerHUDClass.cpp
│   │   │       │   └── PlayerHUDClass.h
│   │   │       └── Weapon
│   │   │           ├── MagicSpellClass.cpp
│   │   │           ├── MagicSpellClass.h
│   │   │           ├── MagicWeaponClass.cpp
│   │   │           ├── MagicWeaponClass.h
│   │   │           ├── MasterWeaponClass.cpp
│   │   │           ├── MasterWeaponClass.h
│   │   │           ├── MeleeWeaponClass.cpp
│   │   │           ├── MeleeWeaponClass.h
│   │   │           ├── WeaponSwapNotify.cpp
│   │   │           └── WeaponSwapNotify.h
│   │   ├── Core
│   │   │   ├── DoorInterface.cpp
│   │   │   ├── DoorInterface.h
│   │   │   ├── DungeonEnemiesHandler.cpp
│   │   │   ├── DungeonEnemiesHandler.h
│   │   │   ├── GamemodeClass.cpp
│   │   │   ├── GamemodeClass.h
│   │   │   ├── MasterRoom.cpp
│   │   │   ├── MasterRoom.h
│   │   │   ├── ProceduralDungeonGenerator.cpp
│   │   │   └── ProceduralDungeonGenerator.h
│   │   ├── DungeonFighter.Build.cs
│   │   ├── DungeonFighter.cpp
│   │   └── DungeonFighter.h
│   ├── DungeonFighterEditor.Target.cs
│   └── DungeonFighter.Target.cs
└── tests
    ├── __init__.py
    ├── test_asset_renaming.py
    └── test_asset_renaming_unittest.py

372 directories, 1709 files
