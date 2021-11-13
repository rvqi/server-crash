# server-crash
ice and fire: foodutils
---- Minecraft Crash Report ----
// Who set us up the TNT?

Time: 11/13/21 8:00 AM
Description: Ticking entity

java.lang.NoClassDefFoundError: com/github/alexthe666/iceandfire/api/FoodUtils
	at com.github.alexthe666.iceandfire.entity.ai.DragonAITargetItems$1.apply(DragonAITargetItems.java:50) ~[iceandfire:2.1.9-1.16.5] {re:classloading}
	at com.github.alexthe666.iceandfire.entity.ai.DragonAITargetItems$1.apply(DragonAITargetItems.java:47) ~[iceandfire:2.1.9-1.16.5] {re:classloading}
	at com.google.common.base.Predicate.test(Predicate.java:80) ~[server-1.16.5-20210115.111550-extra.jar:?] {}
	at net.minecraft.world.chunk.Chunk.func_177430_a(Chunk.java:522) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.world.World.func_225316_b(World.java:789) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at com.github.alexthe666.iceandfire.entity.ai.DragonAITargetItems.func_75250_a(DragonAITargetItems.java:68) ~[iceandfire:2.1.9-1.16.5] {re:classloading}
	at net.minecraft.entity.ai.goal.PrioritizedGoal.func_75250_a(SourceFile:22) ~[?:?] {re:classloading,pl:accesstransformer:B,re:mixin,pl:accesstransformer:B}
	at com.performant.coremod.entity.ai.CustomGoalSelector.func_75774_a(CustomGoalSelector.java:379) ~[performant:1.16.2-5-3.72m] {re:classloading}
	at net.minecraft.entity.MobEntity.func_70626_be(MobEntity.java:679) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:spiderstpo.mixins.json:MobEntityMixin,pl:mixin:APP:charm.mixins.json:accessor.MobEntityAccessor,pl:mixin:APP:improvedmobs.mixins.json:MobEntityMixin,pl:mixin:APP:performant.mixins.json:entity.MobEntityDespawnMixin,pl:mixin:APP:performant.mixins.json:entity.MobEntityMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.entity.LivingEntity.func_70636_d(LivingEntity.java:2411) ~[?:?] {re:mixin,pl:accesstransformer:B,xf:fml:placebo:placeboshieldblock,xf:fml:apotheosis:apothshieldblock,xf:fml:apotheosis:apothpotiondmg,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,xf:fml:placebo:placeboshieldblock,xf:fml:apotheosis:apothshieldblock,xf:fml:apotheosis:apothpotiondmg,pl:mixin:APP:bigbrain.mixins.json:LivingEntityMixin,pl:mixin:APP:supplementaries.mixins.json:LivingEntityMixin,pl:mixin:APP:tenshilib.mixins.json:LivingEntityMixin,pl:mixin:APP:pmmo.mixins.json:LivingEntityChangeRespirationMixin,pl:mixin:APP:assets/offhandcombat/offhandcombat.mixins.json:SwingEntityMixin,pl:mixin:APP:blue_skies.mixins.json:LivingEntityMixin,pl:mixin:APP:eidolon.mixins.json:LivingEntityMixin,pl:mixin:APP:citadel.mixins.json:LivingEntityMixin,pl:mixin:APP:ars_nouveau.mixins.json:ExpInvokerMixin,pl:mixin:APP:ars_nouveau.mixins.json:MixinLivingEntity,pl:mixin:APP:spiderstpo.mixins.json:LivingEntityMixin,pl:mixin:APP:upgrade_aquatic.mixins.json:LivingEntityMixin,pl:mixin:APP:personality.mixins.json:LivingEntityMixin,pl:mixin:APP:charm.mixins.json:LivingEntityMixin,pl:mixin:APP:improvedmobs.mixins.json:GuardianMixin,pl:mixin:APP:expandability.mixins.json:swimming.LivingEntityMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.entity.MobEntity.func_70636_d(MobEntity.java:488) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:spiderstpo.mixins.json:MobEntityMixin,pl:mixin:APP:charm.mixins.json:accessor.MobEntityAccessor,pl:mixin:APP:improvedmobs.mixins.json:MobEntityMixin,pl:mixin:APP:performant.mixins.json:entity.MobEntityDespawnMixin,pl:mixin:APP:performant.mixins.json:entity.MobEntityMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.entity.AgeableEntity.func_70636_d(SourceFile:127) ~[?:?] {re:mixin,re:classloading}
	at net.minecraft.entity.passive.AnimalEntity.func_70636_d(AnimalEntity.java:51) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:randompatches.mixins.json:AnimalEntityMixin,pl:mixin:APP:byg.mixins.json:common.entity.MixinAnimalEntity,pl:mixin:APP:charm.mixins.json:AnimalEntityMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at com.github.alexthe666.iceandfire.entity.EntityDragonBase.func_70636_d(EntityDragonBase.java:1645) ~[iceandfire:2.1.9-1.16.5] {re:classloading,pl:runtimedistcleaner:A}
	at com.github.alexthe666.iceandfire.entity.EntityIceDragon.func_70636_d(EntityIceDragon.java:189) ~[iceandfire:2.1.9-1.16.5] {re:classloading}
	at net.minecraft.entity.LivingEntity.func_70071_h_(LivingEntity.java:2158) ~[?:?] {re:mixin,pl:accesstransformer:B,xf:fml:placebo:placeboshieldblock,xf:fml:apotheosis:apothshieldblock,xf:fml:apotheosis:apothpotiondmg,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,xf:fml:placebo:placeboshieldblock,xf:fml:apotheosis:apothshieldblock,xf:fml:apotheosis:apothpotiondmg,pl:mixin:APP:bigbrain.mixins.json:LivingEntityMixin,pl:mixin:APP:supplementaries.mixins.json:LivingEntityMixin,pl:mixin:APP:tenshilib.mixins.json:LivingEntityMixin,pl:mixin:APP:pmmo.mixins.json:LivingEntityChangeRespirationMixin,pl:mixin:APP:assets/offhandcombat/offhandcombat.mixins.json:SwingEntityMixin,pl:mixin:APP:blue_skies.mixins.json:LivingEntityMixin,pl:mixin:APP:eidolon.mixins.json:LivingEntityMixin,pl:mixin:APP:citadel.mixins.json:LivingEntityMixin,pl:mixin:APP:ars_nouveau.mixins.json:ExpInvokerMixin,pl:mixin:APP:ars_nouveau.mixins.json:MixinLivingEntity,pl:mixin:APP:spiderstpo.mixins.json:LivingEntityMixin,pl:mixin:APP:upgrade_aquatic.mixins.json:LivingEntityMixin,pl:mixin:APP:personality.mixins.json:LivingEntityMixin,pl:mixin:APP:charm.mixins.json:LivingEntityMixin,pl:mixin:APP:improvedmobs.mixins.json:GuardianMixin,pl:mixin:APP:expandability.mixins.json:swimming.LivingEntityMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.entity.MobEntity.func_70071_h_(MobEntity.java:300) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:spiderstpo.mixins.json:MobEntityMixin,pl:mixin:APP:charm.mixins.json:accessor.MobEntityAccessor,pl:mixin:APP:improvedmobs.mixins.json:MobEntityMixin,pl:mixin:APP:performant.mixins.json:entity.MobEntityDespawnMixin,pl:mixin:APP:performant.mixins.json:entity.MobEntityMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at com.github.alexthe666.iceandfire.entity.EntityDragonBase.func_70071_h_(EntityDragonBase.java:1611) ~[iceandfire:2.1.9-1.16.5] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.world.server.ServerWorld.func_217479_a(ServerWorld.java:611) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:performant.mixins.json:world.ServerWorldBlockUpdateMixin,pl:mixin:APP:betternether.mixins.json:ServerWorldMixin,pl:mixin:APP:abnormals_core.mixins.json:ServerWorldMixin,pl:mixin:APP:endergetic.mixins.json:ServerWorldMixin,pl:mixin:APP:quark.mixins.json:ServerWorldMixin,pl:mixin:APP:charm.mixins.json:ServerWorldMixin,pl:mixin:APP:charm.mixins.json:accessor.ServerWorldAccessor,pl:mixin:APP:performant.mixins.json:world.ServerWorldMixin,pl:mixin:APP:performant.mixins.json:entity.MobServerWorldMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.world.World.func_217390_a(World.java:554) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.world.server.ServerWorld.func_72835_b(ServerWorld.java:404) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:performant.mixins.json:world.ServerWorldBlockUpdateMixin,pl:mixin:APP:betternether.mixins.json:ServerWorldMixin,pl:mixin:APP:abnormals_core.mixins.json:ServerWorldMixin,pl:mixin:APP:endergetic.mixins.json:ServerWorldMixin,pl:mixin:APP:quark.mixins.json:ServerWorldMixin,pl:mixin:APP:charm.mixins.json:ServerWorldMixin,pl:mixin:APP:charm.mixins.json:accessor.ServerWorldAccessor,pl:mixin:APP:performant.mixins.json:world.ServerWorldMixin,pl:mixin:APP:performant.mixins.json:entity.MobServerWorldMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.server.MinecraftServer.func_71190_q(MinecraftServer.java:851) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:upstream.mixins.json:MixinMinecraftServer,pl:mixin:APP:blame.mixins.json:MinecraftServerAccessor,pl:mixin:APP:globaldataandresourcepacks.mixins.json:MinecraftServerMixin,pl:mixin:APP:byg.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:charm.mixins.json:accessor.MinecraftServerAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.server.dedicated.DedicatedServer.func_71190_q(DedicatedServer.java:291) ~[?:?] {re:classloading,pl:accesstransformer:B}
	at net.minecraft.server.MinecraftServer.func_71217_p(MinecraftServer.java:787) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:upstream.mixins.json:MixinMinecraftServer,pl:mixin:APP:blame.mixins.json:MinecraftServerAccessor,pl:mixin:APP:globaldataandresourcepacks.mixins.json:MinecraftServerMixin,pl:mixin:APP:byg.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:charm.mixins.json:accessor.MinecraftServerAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.server.MinecraftServer.func_240802_v_(MinecraftServer.java:642) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:upstream.mixins.json:MixinMinecraftServer,pl:mixin:APP:blame.mixins.json:MinecraftServerAccessor,pl:mixin:APP:globaldataandresourcepacks.mixins.json:MinecraftServerMixin,pl:mixin:APP:byg.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:charm.mixins.json:accessor.MinecraftServerAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.server.MinecraftServer.func_240783_a_(MinecraftServer.java:232) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:upstream.mixins.json:MixinMinecraftServer,pl:mixin:APP:blame.mixins.json:MinecraftServerAccessor,pl:mixin:APP:globaldataandresourcepacks.mixins.json:MinecraftServerMixin,pl:mixin:APP:byg.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:charm.mixins.json:accessor.MinecraftServerAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at java.lang.Thread.run(Thread.java:748) [?:1.8.0_271] {}
Caused by: java.lang.ClassNotFoundException: com.github.alexthe666.iceandfire.api.FoodUtils
	at java.lang.ClassLoader.findClass(ClassLoader.java:523) ~[?:1.8.0_271] {}
	at java.lang.ClassLoader.loadClass(ClassLoader.java:418) ~[?:1.8.0_271] {}
	at cpw.mods.modlauncher.TransformingClassLoader.loadClass(TransformingClassLoader.java:106) ~[modlauncher-8.0.9.jar:?] {re:classloading}
	at java.lang.ClassLoader.loadClass(ClassLoader.java:351) ~[?:1.8.0_271] {}
	... 27 more
	Suppressed: java.lang.ClassNotFoundException: Failed to find class bytes for com.github.alexthe666.iceandfire.api.FoodUtils
		at cpw.mods.modlauncher.TransformingClassLoader$DelegatedClassLoader.findClass(TransformingClassLoader.java:260) ~[modlauncher-8.0.9.jar:?] {}
		at cpw.mods.modlauncher.TransformingClassLoader.loadClass(TransformingClassLoader.java:136) ~[modlauncher-8.0.9.jar:?] {re:classloading}
		at cpw.mods.modlauncher.TransformingClassLoader.loadClass(TransformingClassLoader.java:98) ~[modlauncher-8.0.9.jar:?] {re:classloading}
		at java.lang.ClassLoader.loadClass(ClassLoader.java:351) ~[?:1.8.0_271] {}
		at com.github.alexthe666.iceandfire.entity.ai.DragonAITargetItems$1.apply(DragonAITargetItems.java:50) ~[iceandfire:2.1.9-1.16.5] {re:classloading}
		at com.github.alexthe666.iceandfire.entity.ai.DragonAITargetItems$1.apply(DragonAITargetItems.java:47) ~[iceandfire:2.1.9-1.16.5] {re:classloading}
		at com.google.common.base.Predicate.test(Predicate.java:80) ~[server-1.16.5-20210115.111550-extra.jar:?] {}
		at net.minecraft.world.chunk.Chunk.func_177430_a(Chunk.java:522) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
		at net.minecraft.world.World.func_225316_b(World.java:789) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
		at com.github.alexthe666.iceandfire.entity.ai.DragonAITargetItems.func_75250_a(DragonAITargetItems.java:68) ~[iceandfire:2.1.9-1.16.5] {re:classloading}
		at net.minecraft.entity.ai.goal.PrioritizedGoal.func_75250_a(SourceFile:22) ~[?:?] {re:classloading,pl:accesstransformer:B,re:mixin,pl:accesstransformer:B}
		at com.performant.coremod.entity.ai.CustomGoalSelector.func_75774_a(CustomGoalSelector.java:379) ~[performant:1.16.2-5-3.72m] {re:classloading}
		at net.minecraft.entity.MobEntity.func_70626_be(MobEntity.java:679) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:spiderstpo.mixins.json:MobEntityMixin,pl:mixin:APP:charm.mixins.json:accessor.MobEntityAccessor,pl:mixin:APP:improvedmobs.mixins.json:MobEntityMixin,pl:mixin:APP:performant.mixins.json:entity.MobEntityDespawnMixin,pl:mixin:APP:performant.mixins.json:entity.MobEntityMixin,pl:mixin:A,pl:runtimedistcleaner:A}
		at net.minecraft.entity.LivingEntity.func_70636_d(LivingEntity.java:2411) ~[?:?] {re:mixin,pl:accesstransformer:B,xf:fml:placebo:placeboshieldblock,xf:fml:apotheosis:apothshieldblock,xf:fml:apotheosis:apothpotiondmg,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,xf:fml:placebo:placeboshieldblock,xf:fml:apotheosis:apothshieldblock,xf:fml:apotheosis:apothpotiondmg,pl:mixin:APP:bigbrain.mixins.json:LivingEntityMixin,pl:mixin:APP:supplementaries.mixins.json:LivingEntityMixin,pl:mixin:APP:tenshilib.mixins.json:LivingEntityMixin,pl:mixin:APP:pmmo.mixins.json:LivingEntityChangeRespirationMixin,pl:mixin:APP:assets/offhandcombat/offhandcombat.mixins.json:SwingEntityMixin,pl:mixin:APP:blue_skies.mixins.json:LivingEntityMixin,pl:mixin:APP:eidolon.mixins.json:LivingEntityMixin,pl:mixin:APP:citadel.mixins.json:LivingEntityMixin,pl:mixin:APP:ars_nouveau.mixins.json:ExpInvokerMixin,pl:mixin:APP:ars_nouveau.mixins.json:MixinLivingEntity,pl:mixin:APP:spiderstpo.mixins.json:LivingEntityMixin,pl:mixin:APP:upgrade_aquatic.mixins.json:LivingEntityMixin,pl:mixin:APP:personality.mixins.json:LivingEntityMixin,pl:mixin:APP:charm.mixins.json:LivingEntityMixin,pl:mixin:APP:improvedmobs.mixins.json:GuardianMixin,pl:mixin:APP:expandability.mixins.json:swimming.LivingEntityMixin,pl:mixin:A,pl:runtimedistcleaner:A}
		at net.minecraft.entity.MobEntity.func_70636_d(MobEntity.java:488) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:spiderstpo.mixins.json:MobEntityMixin,pl:mixin:APP:charm.mixins.json:accessor.MobEntityAccessor,pl:mixin:APP:improvedmobs.mixins.json:MobEntityMixin,pl:mixin:APP:performant.mixins.json:entity.MobEntityDespawnMixin,pl:mixin:APP:performant.mixins.json:entity.MobEntityMixin,pl:mixin:A,pl:runtimedistcleaner:A}
		at net.minecraft.entity.AgeableEntity.func_70636_d(SourceFile:127) ~[?:?] {re:mixin,re:classloading}
		at net.minecraft.entity.passive.AnimalEntity.func_70636_d(AnimalEntity.java:51) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:randompatches.mixins.json:AnimalEntityMixin,pl:mixin:APP:byg.mixins.json:common.entity.MixinAnimalEntity,pl:mixin:APP:charm.mixins.json:AnimalEntityMixin,pl:mixin:A,pl:runtimedistcleaner:A}
		at com.github.alexthe666.iceandfire.entity.EntityDragonBase.func_70636_d(EntityDragonBase.java:1645) ~[iceandfire:2.1.9-1.16.5] {re:classloading,pl:runtimedistcleaner:A}
		at com.github.alexthe666.iceandfire.entity.EntityIceDragon.func_70636_d(EntityIceDragon.java:189) ~[iceandfire:2.1.9-1.16.5] {re:classloading}
		at net.minecraft.entity.LivingEntity.func_70071_h_(LivingEntity.java:2158) ~[?:?] {re:mixin,pl:accesstransformer:B,xf:fml:placebo:placeboshieldblock,xf:fml:apotheosis:apothshieldblock,xf:fml:apotheosis:apothpotiondmg,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,xf:fml:placebo:placeboshieldblock,xf:fml:apotheosis:apothshieldblock,xf:fml:apotheosis:apothpotiondmg,pl:mixin:APP:bigbrain.mixins.json:LivingEntityMixin,pl:mixin:APP:supplementaries.mixins.json:LivingEntityMixin,pl:mixin:APP:tenshilib.mixins.json:LivingEntityMixin,pl:mixin:APP:pmmo.mixins.json:LivingEntityChangeRespirationMixin,pl:mixin:APP:assets/offhandcombat/offhandcombat.mixins.json:SwingEntityMixin,pl:mixin:APP:blue_skies.mixins.json:LivingEntityMixin,pl:mixin:APP:eidolon.mixins.json:LivingEntityMixin,pl:mixin:APP:citadel.mixins.json:LivingEntityMixin,pl:mixin:APP:ars_nouveau.mixins.json:ExpInvokerMixin,pl:mixin:APP:ars_nouveau.mixins.json:MixinLivingEntity,pl:mixin:APP:spiderstpo.mixins.json:LivingEntityMixin,pl:mixin:APP:upgrade_aquatic.mixins.json:LivingEntityMixin,pl:mixin:APP:personality.mixins.json:LivingEntityMixin,pl:mixin:APP:charm.mixins.json:LivingEntityMixin,pl:mixin:APP:improvedmobs.mixins.json:GuardianMixin,pl:mixin:APP:expandability.mixins.json:swimming.LivingEntityMixin,pl:mixin:A,pl:runtimedistcleaner:A}
		at net.minecraft.entity.MobEntity.func_70071_h_(MobEntity.java:300) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:spiderstpo.mixins.json:MobEntityMixin,pl:mixin:APP:charm.mixins.json:accessor.MobEntityAccessor,pl:mixin:APP:improvedmobs.mixins.json:MobEntityMixin,pl:mixin:APP:performant.mixins.json:entity.MobEntityDespawnMixin,pl:mixin:APP:performant.mixins.json:entity.MobEntityMixin,pl:mixin:A,pl:runtimedistcleaner:A}
		at com.github.alexthe666.iceandfire.entity.EntityDragonBase.func_70071_h_(EntityDragonBase.java:1611) ~[iceandfire:2.1.9-1.16.5] {re:classloading,pl:runtimedistcleaner:A}
		at net.minecraft.world.server.ServerWorld.func_217479_a(ServerWorld.java:611) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:performant.mixins.json:world.ServerWorldBlockUpdateMixin,pl:mixin:APP:betternether.mixins.json:ServerWorldMixin,pl:mixin:APP:abnormals_core.mixins.json:ServerWorldMixin,pl:mixin:APP:endergetic.mixins.json:ServerWorldMixin,pl:mixin:APP:quark.mixins.json:ServerWorldMixin,pl:mixin:APP:charm.mixins.json:ServerWorldMixin,pl:mixin:APP:charm.mixins.json:accessor.ServerWorldAccessor,pl:mixin:APP:performant.mixins.json:world.ServerWorldMixin,pl:mixin:APP:performant.mixins.json:entity.MobServerWorldMixin,pl:mixin:A,pl:runtimedistcleaner:A}
		at net.minecraft.world.World.func_217390_a(World.java:554) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
		at net.minecraft.world.server.ServerWorld.func_72835_b(ServerWorld.java:404) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:performant.mixins.json:world.ServerWorldBlockUpdateMixin,pl:mixin:APP:betternether.mixins.json:ServerWorldMixin,pl:mixin:APP:abnormals_core.mixins.json:ServerWorldMixin,pl:mixin:APP:endergetic.mixins.json:ServerWorldMixin,pl:mixin:APP:quark.mixins.json:ServerWorldMixin,pl:mixin:APP:charm.mixins.json:ServerWorldMixin,pl:mixin:APP:charm.mixins.json:accessor.ServerWorldAccessor,pl:mixin:APP:performant.mixins.json:world.ServerWorldMixin,pl:mixin:APP:performant.mixins.json:entity.MobServerWorldMixin,pl:mixin:A,pl:runtimedistcleaner:A}
		at net.minecraft.server.MinecraftServer.func_71190_q(MinecraftServer.java:851) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:upstream.mixins.json:MixinMinecraftServer,pl:mixin:APP:blame.mixins.json:MinecraftServerAccessor,pl:mixin:APP:globaldataandresourcepacks.mixins.json:MinecraftServerMixin,pl:mixin:APP:byg.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:charm.mixins.json:accessor.MinecraftServerAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
		at net.minecraft.server.dedicated.DedicatedServer.func_71190_q(DedicatedServer.java:291) ~[?:?] {re:classloading,pl:accesstransformer:B}
		at net.minecraft.server.MinecraftServer.func_71217_p(MinecraftServer.java:787) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:upstream.mixins.json:MixinMinecraftServer,pl:mixin:APP:blame.mixins.json:MinecraftServerAccessor,pl:mixin:APP:globaldataandresourcepacks.mixins.json:MinecraftServerMixin,pl:mixin:APP:byg.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:charm.mixins.json:accessor.MinecraftServerAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
		at net.minecraft.server.MinecraftServer.func_240802_v_(MinecraftServer.java:642) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:upstream.mixins.json:MixinMinecraftServer,pl:mixin:APP:blame.mixins.json:MinecraftServerAccessor,pl:mixin:APP:globaldataandresourcepacks.mixins.json:MinecraftServerMixin,pl:mixin:APP:byg.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:charm.mixins.json:accessor.MinecraftServerAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
		at net.minecraft.server.MinecraftServer.func_240783_a_(MinecraftServer.java:232) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:upstream.mixins.json:MixinMinecraftServer,pl:mixin:APP:blame.mixins.json:MinecraftServerAccessor,pl:mixin:APP:globaldataandresourcepacks.mixins.json:MinecraftServerMixin,pl:mixin:APP:byg.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:charm.mixins.json:accessor.MinecraftServerAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
		at java.lang.Thread.run(Thread.java:748) [?:1.8.0_271] {}
	Caused by: java.nio.channels.ClosedChannelException
		at sun.nio.ch.FileChannelImpl.ensureOpen(FileChannelImpl.java:110) ~[?:1.8.0_271] {}
		at sun.nio.ch.FileChannelImpl.position(FileChannelImpl.java:276) ~[?:1.8.0_271] {}
		at sun.nio.ch.FileChannelImpl.position(FileChannelImpl.java:50) ~[?:1.8.0_271] {}
		at com.sun.nio.zipfs.ZipFileSystem.readFullyAt(ZipFileSystem.java:952) ~[zipfs.jar:1.8.0_271] {}
		at com.sun.nio.zipfs.ZipFileSystem.readFullyAt(ZipFileSystem.java:945) ~[zipfs.jar:1.8.0_271] {}
		at com.sun.nio.zipfs.ZipFileSystem.getDataPos(ZipFileSystem.java:931) ~[zipfs.jar:1.8.0_271] {}
		at com.sun.nio.zipfs.ZipFileSystem.access$400(ZipFileSystem.java:80) ~[zipfs.jar:1.8.0_271] {}
		at com.sun.nio.zipfs.ZipFileSystem$EntryInputStream.<init>(ZipFileSystem.java:1500) ~[zipfs.jar:1.8.0_271] {}
		at com.sun.nio.zipfs.ZipFileSystem.getInputStream(ZipFileSystem.java:1430) ~[zipfs.jar:1.8.0_271] {}
		at com.sun.nio.zipfs.ZipFileSystem.newInputStream(ZipFileSystem.java:547) ~[zipfs.jar:1.8.0_271] {}
		at com.sun.nio.zipfs.ZipPath.newInputStream(ZipPath.java:645) ~[zipfs.jar:1.8.0_271] {}
		at com.sun.nio.zipfs.ZipFileSystemProvider.newInputStream(ZipFileSystemProvider.java:278) ~[zipfs.jar:1.8.0_271] {}
		at java.nio.file.Files.newInputStream(Files.java:152) ~[?:1.8.0_271] {}
		at net.minecraftforge.fml.loading.ModJarURLHandler$ModJarURLConnection.getInputStream(ModJarURLHandler.java:87) ~[mineshafts_and_monsters_1.8.2.jar:36.2] {}
		at cpw.mods.modlauncher.TransformingClassLoader$AutoURLConnection.<init>(TransformingClassLoader.java:174) ~[modlauncher-8.0.9.jar:?] {}
		at cpw.mods.modlauncher.TransformingClassLoader$DelegatedClassLoader.findClass(TransformingClassLoader.java:247) ~[modlauncher-8.0.9.jar:?] {}
		... 30 more


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Thread: Server thread
Stacktrace:
	at com.github.alexthe666.iceandfire.entity.ai.DragonAITargetItems$1.apply(DragonAITargetItems.java:50) ~[iceandfire:2.1.9-1.16.5] {re:classloading}
	at com.github.alexthe666.iceandfire.entity.ai.DragonAITargetItems$1.apply(DragonAITargetItems.java:47) ~[iceandfire:2.1.9-1.16.5] {re:classloading}
	at com.google.common.base.Predicate.test(Predicate.java:80) ~[server-1.16.5-20210115.111550-extra.jar:?] {}
	at net.minecraft.world.chunk.Chunk.func_177430_a(Chunk.java:522) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.world.World.func_225316_b(World.java:789) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at com.github.alexthe666.iceandfire.entity.ai.DragonAITargetItems.func_75250_a(DragonAITargetItems.java:68) ~[iceandfire:2.1.9-1.16.5] {re:classloading}
	at net.minecraft.entity.ai.goal.PrioritizedGoal.func_75250_a(SourceFile:22) ~[?:?] {re:classloading,pl:accesstransformer:B,re:mixin,pl:accesstransformer:B}
	at com.performant.coremod.entity.ai.CustomGoalSelector.func_75774_a(CustomGoalSelector.java:379) ~[performant:1.16.2-5-3.72m] {re:classloading}
	at net.minecraft.entity.MobEntity.func_70626_be(MobEntity.java:679) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:spiderstpo.mixins.json:MobEntityMixin,pl:mixin:APP:charm.mixins.json:accessor.MobEntityAccessor,pl:mixin:APP:improvedmobs.mixins.json:MobEntityMixin,pl:mixin:APP:performant.mixins.json:entity.MobEntityDespawnMixin,pl:mixin:APP:performant.mixins.json:entity.MobEntityMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.entity.LivingEntity.func_70636_d(LivingEntity.java:2411) ~[?:?] {re:mixin,pl:accesstransformer:B,xf:fml:placebo:placeboshieldblock,xf:fml:apotheosis:apothshieldblock,xf:fml:apotheosis:apothpotiondmg,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,xf:fml:placebo:placeboshieldblock,xf:fml:apotheosis:apothshieldblock,xf:fml:apotheosis:apothpotiondmg,pl:mixin:APP:bigbrain.mixins.json:LivingEntityMixin,pl:mixin:APP:supplementaries.mixins.json:LivingEntityMixin,pl:mixin:APP:tenshilib.mixins.json:LivingEntityMixin,pl:mixin:APP:pmmo.mixins.json:LivingEntityChangeRespirationMixin,pl:mixin:APP:assets/offhandcombat/offhandcombat.mixins.json:SwingEntityMixin,pl:mixin:APP:blue_skies.mixins.json:LivingEntityMixin,pl:mixin:APP:eidolon.mixins.json:LivingEntityMixin,pl:mixin:APP:citadel.mixins.json:LivingEntityMixin,pl:mixin:APP:ars_nouveau.mixins.json:ExpInvokerMixin,pl:mixin:APP:ars_nouveau.mixins.json:MixinLivingEntity,pl:mixin:APP:spiderstpo.mixins.json:LivingEntityMixin,pl:mixin:APP:upgrade_aquatic.mixins.json:LivingEntityMixin,pl:mixin:APP:personality.mixins.json:LivingEntityMixin,pl:mixin:APP:charm.mixins.json:LivingEntityMixin,pl:mixin:APP:improvedmobs.mixins.json:GuardianMixin,pl:mixin:APP:expandability.mixins.json:swimming.LivingEntityMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.entity.MobEntity.func_70636_d(MobEntity.java:488) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:spiderstpo.mixins.json:MobEntityMixin,pl:mixin:APP:charm.mixins.json:accessor.MobEntityAccessor,pl:mixin:APP:improvedmobs.mixins.json:MobEntityMixin,pl:mixin:APP:performant.mixins.json:entity.MobEntityDespawnMixin,pl:mixin:APP:performant.mixins.json:entity.MobEntityMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.entity.AgeableEntity.func_70636_d(SourceFile:127) ~[?:?] {re:mixin,re:classloading}
	at net.minecraft.entity.passive.AnimalEntity.func_70636_d(AnimalEntity.java:51) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:randompatches.mixins.json:AnimalEntityMixin,pl:mixin:APP:byg.mixins.json:common.entity.MixinAnimalEntity,pl:mixin:APP:charm.mixins.json:AnimalEntityMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at com.github.alexthe666.iceandfire.entity.EntityDragonBase.func_70636_d(EntityDragonBase.java:1645) ~[iceandfire:2.1.9-1.16.5] {re:classloading,pl:runtimedistcleaner:A}
	at com.github.alexthe666.iceandfire.entity.EntityIceDragon.func_70636_d(EntityIceDragon.java:189) ~[iceandfire:2.1.9-1.16.5] {re:classloading}
	at net.minecraft.entity.LivingEntity.func_70071_h_(LivingEntity.java:2158) ~[?:?] {re:mixin,pl:accesstransformer:B,xf:fml:placebo:placeboshieldblock,xf:fml:apotheosis:apothshieldblock,xf:fml:apotheosis:apothpotiondmg,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,xf:fml:placebo:placeboshieldblock,xf:fml:apotheosis:apothshieldblock,xf:fml:apotheosis:apothpotiondmg,pl:mixin:APP:bigbrain.mixins.json:LivingEntityMixin,pl:mixin:APP:supplementaries.mixins.json:LivingEntityMixin,pl:mixin:APP:tenshilib.mixins.json:LivingEntityMixin,pl:mixin:APP:pmmo.mixins.json:LivingEntityChangeRespirationMixin,pl:mixin:APP:assets/offhandcombat/offhandcombat.mixins.json:SwingEntityMixin,pl:mixin:APP:blue_skies.mixins.json:LivingEntityMixin,pl:mixin:APP:eidolon.mixins.json:LivingEntityMixin,pl:mixin:APP:citadel.mixins.json:LivingEntityMixin,pl:mixin:APP:ars_nouveau.mixins.json:ExpInvokerMixin,pl:mixin:APP:ars_nouveau.mixins.json:MixinLivingEntity,pl:mixin:APP:spiderstpo.mixins.json:LivingEntityMixin,pl:mixin:APP:upgrade_aquatic.mixins.json:LivingEntityMixin,pl:mixin:APP:personality.mixins.json:LivingEntityMixin,pl:mixin:APP:charm.mixins.json:LivingEntityMixin,pl:mixin:APP:improvedmobs.mixins.json:GuardianMixin,pl:mixin:APP:expandability.mixins.json:swimming.LivingEntityMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.entity.MobEntity.func_70071_h_(MobEntity.java:300) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:spiderstpo.mixins.json:MobEntityMixin,pl:mixin:APP:charm.mixins.json:accessor.MobEntityAccessor,pl:mixin:APP:improvedmobs.mixins.json:MobEntityMixin,pl:mixin:APP:performant.mixins.json:entity.MobEntityDespawnMixin,pl:mixin:APP:performant.mixins.json:entity.MobEntityMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at com.github.alexthe666.iceandfire.entity.EntityDragonBase.func_70071_h_(EntityDragonBase.java:1611) ~[iceandfire:2.1.9-1.16.5] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.world.server.ServerWorld.func_217479_a(ServerWorld.java:611) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:performant.mixins.json:world.ServerWorldBlockUpdateMixin,pl:mixin:APP:betternether.mixins.json:ServerWorldMixin,pl:mixin:APP:abnormals_core.mixins.json:ServerWorldMixin,pl:mixin:APP:endergetic.mixins.json:ServerWorldMixin,pl:mixin:APP:quark.mixins.json:ServerWorldMixin,pl:mixin:APP:charm.mixins.json:ServerWorldMixin,pl:mixin:APP:charm.mixins.json:accessor.ServerWorldAccessor,pl:mixin:APP:performant.mixins.json:world.ServerWorldMixin,pl:mixin:APP:performant.mixins.json:entity.MobServerWorldMixin,pl:mixin:A,pl:runtimedistcleaner:A}
-- Entity being ticked --
Details:
	Entity Type: iceandfire:ice_dragon (com.github.alexthe666.iceandfire.entity.EntityIceDragon)
	Entity ID: 442063
	Entity Name: Ice Dragon
	Entity's Exact location: -555.75, 67.13, -894.51
	Entity's Block location: World: (-556,67,-895), Chunk: (at 4,4,1 in -35,-56; contains blocks -560,0,-896 to -545,255,-881), Region: (-2,-2; contains chunks -64,-64 to -33,-33, blocks -1024,0,-1024 to -513,255,-513)
	Entity's Momentum: -0.13, 0.33, -0.12
	Entity's Passengers: []
	Entity's Vehicle: ~~ERROR~~ NullPointerException: null
Stacktrace:
	at net.minecraft.world.World.func_217390_a(World.java:554) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.world.server.ServerWorld.func_72835_b(ServerWorld.java:404) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:performant.mixins.json:world.ServerWorldBlockUpdateMixin,pl:mixin:APP:betternether.mixins.json:ServerWorldMixin,pl:mixin:APP:abnormals_core.mixins.json:ServerWorldMixin,pl:mixin:APP:endergetic.mixins.json:ServerWorldMixin,pl:mixin:APP:quark.mixins.json:ServerWorldMixin,pl:mixin:APP:charm.mixins.json:ServerWorldMixin,pl:mixin:APP:charm.mixins.json:accessor.ServerWorldAccessor,pl:mixin:APP:performant.mixins.json:world.ServerWorldMixin,pl:mixin:APP:performant.mixins.json:entity.MobServerWorldMixin,pl:mixin:A,pl:runtimedistcleaner:A}


-- Affected level --
Details:
	All players: 1 total; [ServerPlayerEntity['Takemaroo'/437387, l='ServerLevel[Mineham]', x=-556.47, y=64.00, z=-967.39]]
	Chunk stats: ServerChunkCache: 3546
	Level dimension: minecraft:overworld
	Level spawn location: World: (-176,75,-223), Chunk: (at 0,4,1 in -11,-14; contains blocks -176,0,-224 to -161,255,-209), Region: (-1,-1; contains chunks -32,-32 to -1,-1, blocks -512,0,-512 to -1,255,-1)
	Level time: 3848480 game time, 4185708 day time
	Level name: Mineham
	Level game mode: Game mode: survival (ID 0). Hardcore: false. Cheats: false
	Level weather: Rain time: 112885 (now: false), thunder time: 150768 (now: false)
	Known server brands: forge
	Level was modded: true
	Level storage version: 0x04ABD - Anvil
Stacktrace:
	at net.minecraft.server.MinecraftServer.func_71190_q(MinecraftServer.java:851) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:upstream.mixins.json:MixinMinecraftServer,pl:mixin:APP:blame.mixins.json:MinecraftServerAccessor,pl:mixin:APP:globaldataandresourcepacks.mixins.json:MinecraftServerMixin,pl:mixin:APP:byg.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:charm.mixins.json:accessor.MinecraftServerAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.server.dedicated.DedicatedServer.func_71190_q(DedicatedServer.java:291) ~[?:?] {re:classloading,pl:accesstransformer:B}
	at net.minecraft.server.MinecraftServer.func_71217_p(MinecraftServer.java:787) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:upstream.mixins.json:MixinMinecraftServer,pl:mixin:APP:blame.mixins.json:MinecraftServerAccessor,pl:mixin:APP:globaldataandresourcepacks.mixins.json:MinecraftServerMixin,pl:mixin:APP:byg.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:charm.mixins.json:accessor.MinecraftServerAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.server.MinecraftServer.func_240802_v_(MinecraftServer.java:642) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:upstream.mixins.json:MixinMinecraftServer,pl:mixin:APP:blame.mixins.json:MinecraftServerAccessor,pl:mixin:APP:globaldataandresourcepacks.mixins.json:MinecraftServerMixin,pl:mixin:APP:byg.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:charm.mixins.json:accessor.MinecraftServerAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.server.MinecraftServer.func_240783_a_(MinecraftServer.java:232) ~[?:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:upstream.mixins.json:MixinMinecraftServer,pl:mixin:APP:blame.mixins.json:MinecraftServerAccessor,pl:mixin:APP:globaldataandresourcepacks.mixins.json:MinecraftServerMixin,pl:mixin:APP:byg.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:charm.mixins.json:accessor.MinecraftServerAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at java.lang.Thread.run(Thread.java:748) [?:1.8.0_271] {}


-- System Details --
Details:
	Minecraft Version: 1.16.5
	Minecraft Version ID: 1.16.5
	Operating System: Linux (amd64) version 4.15.0-128-generic
	Java Version: 1.8.0_271, Oracle Corporation
	Java VM Version: Java HotSpot(TM) 64-Bit Server VM (mixed mode), Oracle Corporation
	Memory: 955398592 bytes (911 MB) / 3715104768 bytes (3543 MB) up to 6442450944 bytes (6144 MB)
	CPUs: 16
	JVM Flags: 4 total; -Xmx6144M -Xms512M -XX:+UseG1GC -Xss2M
	ModLauncher: 8.0.9+86+master.3cf110c
	ModLauncher launch target: fmlserver
	ModLauncher naming: srg
	ModLauncher services: 
		/mixin-0.8.4.jar mixin PLUGINSERVICE 
		/eventbus-4.0.0.jar eventbus PLUGINSERVICE 
		/mineshafts_and_monsters_1.8.2.jar object_holder_definalize PLUGINSERVICE 
		/mineshafts_and_monsters_1.8.2.jar runtime_enum_extender PLUGINSERVICE 
		/accesstransformers-3.0.1.jar accesstransformer PLUGINSERVICE 
		/mineshafts_and_monsters_1.8.2.jar capability_inject_definalize PLUGINSERVICE 
		/mineshafts_and_monsters_1.8.2.jar runtimedistcleaner PLUGINSERVICE 
		/mixin-0.8.4.jar mixin TRANSFORMATIONSERVICE 
		/mineshafts_and_monsters_1.8.2.jar fml TRANSFORMATIONSERVICE 
	FML: 36.2
	Forge: net.minecraftforge:36.2.8
	FML Language Providers: 
		javafml@36.2
		minecraft@1
		kotlinforforge@1.15.1
	Mod List: 
		BetterDungeons-1.16.4-1.2.1.jar                   |YUNG's Better Dungeons        |betterdungeons                |1.16.4-1.2.1        |DONE      |Manifest: NOSIGNATURE
		bigbrain-1.2.4.jar                                |Big Brain                     |bigbrain                      |1.2.4               |DONE      |Manifest: NOSIGNATURE
		infernal-expansion-2.3.2.jar                      |Infernal Expansion            |infernalexp                   |2.3.2               |DONE      |Manifest: NOSIGNATURE
		ElenaiDodge-1.16.2-1.7.2.jar                      |Elenai Dodge                  |elenaidodge                   |1.16.2-1.7.2        |DONE      |Manifest: NOSIGNATURE
		nether-s-exoticism-1.16.5-1.1.1.jar               |Nether's Exoticism            |nethers_exoticism             |1.1.1               |DONE      |Manifest: NOSIGNATURE
		BetterNether_Reforged-1.1.1.jar                   |Better Nether Reforged        |betternether                  |1.1                 |DONE      |Manifest: NOSIGNATURE
		stalwart-dungeons-1.16.5-1.1.7.jar                |Stalwart Dungeons             |stalwart_dungeons             |1.1.7               |DONE      |Manifest: NOSIGNATURE
		strawgolem-1.16-1.9.jar                           |Straw Golem                   |strawgolem                    |1.16-1.9            |DONE      |Manifest: NOSIGNATURE
		looot-1.16.4-1.0.0.3.jar                          |Looot                         |looot                         |1.0.0.3             |DONE      |Manifest: NOSIGNATURE
		BetterCaves-Forge-1.16.4-1.1.2.jar                |YUNG's Better Caves           |bettercaves                   |1.16.4-1.1.2        |DONE      |Manifest: NOSIGNATURE
		farmersdelightintegrations-1.16.5-1.2.jar         |Farmer's Delight Compats      |farmersdelightintegrations    |1.16.5-1.2          |DONE      |Manifest: NOSIGNATURE
		YungsApi-1.16.4-Forge-13.jar                      |YUNG's API                    |yungsapi                      |1.16.4-Forge-13     |DONE      |Manifest: NOSIGNATURE
		pyromancer 1.6.3.jar                              |Pyromancer                    |pyromancer                    |1.6.3               |DONE      |Manifest: NOSIGNATURE
		reliquary-1.16.5-1.3.5.1100.jar                   |Reliquary                     |xreliquary                    |1.16.5-1.3.5.1100   |DONE      |Manifest: NOSIGNATURE
		lootbeams-1.16.5-release-sept0621.jar             |LootBeams                     |lootbeams                     |1.16.5              |DONE      |Manifest: NOSIGNATURE
		guardvillagers-1.16.5.1.2.6.jar                   |Guard Villagers               |guardvillagers                |1.2.6               |DONE      |Manifest: NOSIGNATURE
		randompatches-2.4.4-forge.jar                     |RandomPatches                 |randompatches                 |2.4.4-forge         |DONE      |Manifest: 92:f6:29:d4:09:89:f5:f5:98:5e:20:34:31:d0:7b:58:22:06:bd:a5:d1:6a:92:6e:ac:3d:8d:18:c5:b2:5b:d7
		Apotheosis-1.16.5-4.8.2.jar                       |Apotheosis                    |apotheosis                    |4.8.2               |DONE      |Manifest: NOSIGNATURE
		Hornets-0.0.3.jar                                 |Hornets                       |hornets                       |0.0.3               |DONE      |Manifest: NOSIGNATURE
		SnowRealMagic-1.16.4-2.7.2.jar                    |Snow! Real Magic!             |snowrealmagic                 |2.7.2               |DONE      |Manifest: NOSIGNATURE
		JustEnoughResources-1.16.5-0.12.1.128.jar         |Just Enough Resources         |jeresources                   |0.12.1.128          |DONE      |Manifest: NOSIGNATURE
		Paraglider-1.16.5-1.3.2.2.jar                     |Paraglider                    |paraglider                    |1.3.2.2             |DONE      |Manifest: NOSIGNATURE
		RevampedWolf-1.16.4-0.7.1.jar                     |RevampedWolf                  |revampedwolf                  |1.16.4-0.7.1        |DONE      |Manifest: NOSIGNATURE
		supplementaries-1.16.5-0.17.2.jar                 |Supplementaries               |supplementaries               |1.16.5-0.17.2       |DONE      |Manifest: NOSIGNATURE
		structure_gel-1.16.5-1.7.8.jar                    |Structure Gel API             |structure_gel                 |1.7.8               |DONE      |Manifest: NOSIGNATURE
		corpse-1.16.5-1.0.6.jar                           |Corpse                        |corpse                        |1.16.5-1.0.6        |DONE      |Manifest: NOSIGNATURE
		AdvancementPlaques-1.16.5-1.4.1.jar               |Advancement Plaques           |advancementplaques            |1.4.1               |DONE      |Manifest: NOSIGNATURE
		castle_in_the_sky-1.16.5-0.2.6.jar                |Castle in the sky             |castle_in_the_sky             |1.16.5              |DONE      |Manifest: NOSIGNATURE
		TenshiLib-1.16.3-1.3.0.jar                        |TenshiLib                     |tenshilib                     |1.16.3-1.3.0        |DONE      |Manifest: NOSIGNATURE
		cleancut-mc1.16-2.2-forge.jar                     |Clean Cut                     |cleancut                      |2.2                 |DONE      |Manifest: NOSIGNATURE
		morevillagers-FORGE-1.16.5-1.5.5.jar              |More Villagers                |morevillagers                 |1.5.5               |DONE      |Manifest: NOSIGNATURE
		BiomesOPlenty-1.16.5-13.1.0.477-universal.jar     |Biomes O' Plenty              |biomesoplenty                 |1.16.5-13.1.0.477   |DONE      |Manifest: NOSIGNATURE
		geode-1.1.2.jar                                   |Geode                         |geode                         |1.0.0               |DONE      |Manifest: NOSIGNATURE
		dungeons_plus-1.16.5-1.1.5.jar                    |Dungeons Plus                 |dungeons_plus                 |1.1.5               |DONE      |Manifest: NOSIGNATURE
		SimplyImprovedTerrain-0.3.2-Forge.jar             |Simply Improved Terrain       |simplyimprovedterrain         |0.3.2-Forge         |DONE      |Manifest: NOSIGNATURE
		extcaves-2.4.jar                                  |Extended Caves                |extcaves                      |2.4                 |DONE      |Manifest: NOSIGNATURE
		BetterDefaultBiomes-1.16.4+-Alpha 2.5.3.jar       |Better Default Biomes         |betterdefaultbiomes           |Alpha 2.5.3         |DONE      |Manifest: NOSIGNATURE
		Highlighter-1.16.5-1.1.0.jar                      |Highlighter                   |highlighter                   |1.1.0               |DONE      |Manifest: NOSIGNATURE
		spark-forge.jar                                   |spark                         |spark                         |1.6.0               |DONE      |Manifest: NOSIGNATURE
		RoRmod-1.1.4.jar                                  |Risk of Rain Mod              |riskofrainmod                 |1.1.4               |DONE      |Manifest: NOSIGNATURE
		curios-forge-1.16.5-4.0.5.3.jar                   |Curios API                    |curios                        |1.16.5-4.0.5.3      |DONE      |Manifest: NOSIGNATURE
		levelhearts-1.16.2-2.2.0.jar                      |LevelHearts                   |levelhearts                   |2.2.0               |DONE      |Manifest: NOSIGNATURE
		specialai-1.16.5-1.0.2.jar                        |Special AI                    |specialai                     |NONE                |DONE      |Manifest: NOSIGNATURE
		RottenPiglinsBug_Fix.jar                          |Rotten_Piglins                |rotten_piglins                |1.1.1               |DONE      |Manifest: NOSIGNATURE
		YungsExtras-Forge-1.16.4-1.0.jar                  |YUNG's Extras                 |yungsextras                   |Forge-1.16.4-1.0    |DONE      |Manifest: NOSIGNATURE
		MushroomQuest_1.16.5_v3.2.jar                     |Mushroom Quest                |mushroomquest                 |3.0.0               |DONE      |Manifest: NOSIGNATURE
		knights_1.16.5_2.jar                              |knights                       |knights                       |1.0.0               |DONE      |Manifest: NOSIGNATURE
		obfuscate-0.6.2-1.16.3.jar                        |Obfuscate                     |obfuscate                     |0.6.2               |DONE      |Manifest: e1:59:1a:56:ec:97:b3:d0:b3:4b:25:06:1f:83:b0:f4:fd:0c:24:e3:6d:ea:94:b1:9f:22:b0:38:13:60:88:ea
		Atlas-Lib-1.16.5-1.1.2.jar                        |Atlas Lib                     |atlaslib                      |1.1.2               |DONE      |Manifest: NOSIGNATURE
		majruszs-difficulty-1.16.4-1.1.0.jar              |Majrusz's Progressive Difficul|majruszs_difficulty           |1.1.0               |DONE      |Manifest: NOSIGNATURE
		sapience-1.16.5-1.1.2.jar                         |Sapience                      |sapience                      |1.1.2               |DONE      |Manifest: NOSIGNATURE
		Project_MMO-1.16.5-3.57.1.jar                     |Project MMO                   |pmmo                          |1.16.5-3.57.1       |DONE      |Manifest: NOSIGNATURE
		mutantmore-1.16.5-1.0.0.jar                       |Mutant More                   |mutantmore                    |1.0.3               |DONE      |Manifest: NOSIGNATURE
		NetherSkeletons3.jar                              |NetherSkeletons               |netherskeletons               |1.0.0               |DONE      |Manifest: NOSIGNATURE
		forestcraft-1.602.jar                             |Astemir's Forest Craft        |forestcraft                   |1.602               |DONE      |Manifest: NOSIGNATURE
		cloth-config-4.11.26-forge.jar                    |Cloth Config v4 API           |cloth-config                  |4.11.26             |DONE      |Manifest: NOSIGNATURE
		toms_storage-1.2.19.jar                           |Tom's Simple Storage Mod      |toms_storage                  |1.2.19              |DONE      |Manifest: NOSIGNATURE
		CustomStartingGear-1.16.4-2.0.2.1-universal.jar   |Custom Starter Gear           |customstartinggear            |2.0.2.1             |DONE      |Manifest: NOSIGNATURE
		exoticbirds-1.16.4-1.2.0.jar                      |Exotic Birds                  |exoticbirds                   |1.2.0               |DONE      |Manifest: NOSIGNATURE
		BetterMineshafts-Forge-1.16.4-2.0.4.jar           |YUNG's Better Mineshafts      |bettermineshafts              |1.16.4-2.0.4        |DONE      |Manifest: NOSIGNATURE
		tree_felling-2.3.jar                              |Tree Felling                  |tree_felling                  |2.3                 |DONE      |Manifest: NOSIGNATURE
		dungeons_gear-1.16.5-3.0.16.jar                   |Dungeons Gear                 |dungeons_gear                 |3.0.16              |DONE      |Manifest: NOSIGNATURE
		Kiwi-1.16.5-3.5.1.jar                             |Kiwi                          |kiwi                          |3.5.1               |DONE      |Manifest: NOSIGNATURE
		BetterAnimationsCollection-v1.2.2-1.16.5.jar      |Better Animations Collection  |betteranimationscollection    |1.2.2               |DONE      |Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		mowziesmobs-1.5.19.jar                            |Mowzie's Mobs                 |mowziesmobs                   |1.5.19              |DONE      |Manifest: NOSIGNATURE
		jei-1.16.5-7.7.1.129.jar                          |Just Enough Items             |jei                           |7.7.1.129           |DONE      |Manifest: NOSIGNATURE
		enderlinginvaders-1.16.5-1.0.4.jar                |Enderling Invaders            |enderlinginvaders             |1.0.3               |DONE      |Manifest: NOSIGNATURE
		Comfortable Nether 4.10.jar                       |Comfortable Nether            |comfortable_nether            |1.0.0               |DONE      |Manifest: NOSIGNATURE
		seals-1.16.3-2.1.2.jar                            |Seals                         |seals                         |2.1.2               |DONE      |Manifest: NOSIGNATURE
		Kobolds-1.4.7.jar                                 |Kobolds                       |kobolds                       |1.0.0               |DONE      |Manifest: NOSIGNATURE
		PassableFoliage-1.16.5-2.4.0.jar                  |Passable Foliage              |passablefoliage               |2.4.0               |DONE      |Manifest: NOSIGNATURE
		HarderBranchMining-1.36.0.9.jar                   |Harder Branch Mining Mod      |harderbranchmining            |1.36.0.9            |DONE      |Manifest: NOSIGNATURE
		NaturesCompass-1.16.5-1.9.1-forge.jar             |Nature's Compass              |naturescompass                |1.16.5-1.9.1-forge  |DONE      |Manifest: NOSIGNATURE
		untamedwilds-1.16.5-1.4.1.jar                     |Untamed Wilds                 |untamedwilds                  |1.4.1               |DONE      |Manifest: NOSIGNATURE
		LibX-1.16.3-1.0.76.jar                            |LibX                          |libx                          |1.16.3-1.0.76       |DONE      |Manifest: NOSIGNATURE
		stoneholm-1.2.2.jar                               |Stoneholm                     |stoneholm                     |1.2                 |DONE      |Manifest: NOSIGNATURE
		upstream-1.0.jar                                  |Upstream                      |upstream                      |1.0                 |DONE      |Manifest: NOSIGNATURE
		champions-forge-1.16.5-2.0.1.7.jar                |Champions                     |champions                     |1.16.5-2.0.1.7      |DONE      |Manifest: NOSIGNATURE
		snowundertrees-1.16.5-v1.3.jar                    |Snow Under Trees              |snowundertrees                |v1.3                |DONE      |Manifest: NOSIGNATURE
		sulfuric-1.1.jar                                  |Sulfuric                      |sulfuric                      |1.0                 |DONE      |Manifest: NOSIGNATURE
		JEITweaker-1.16.5-1.0.1.27.jar                    |JEI Tweaker                   |jeitweaker                    |1.0.1.27            |DONE      |Manifest: NOSIGNATURE
		CraftTweaker-1.16.5-7.1.2.454.jar                 |CraftTweaker                  |crafttweaker                  |7.1.2.454           |DONE      |Manifest: NOSIGNATURE
		GameStages-Forge-1.16.5-7.3.12.jar                |GameStages                    |gamestages                    |7.3.12              |DONE      |Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		restored_earth-1.16.5-1.1.1.jar                   |Restored Earth                |restored_earth                |1.1.1               |DONE      |Manifest: NOSIGNATURE
		forge-1.16.5-36.2.8-universal.jar                 |Forge                         |forge                         |36.2.8              |DONE      |Manifest: 22:af:21:d8:19:82:7f:93:94:fe:2b:ac:b7:e4:41:57:68:39:87:b1:a7:5c:c6:44:f9:25:74:21:14:f5:0d:90
		OffHandCombat-1.16.3-3.2.0.3.jar                  |Off Hand Combat               |offhandcombat                 |1.16.3-3.2.0.3      |DONE      |Manifest: c9:84:cd:eb:27:ac:0d:ad:8c:55:6f:d6:5f:19:f2:c8:63:2a:b0:bd:3b:d0:b6:df:fd:9f:de:9f:9d:e8:7c:68
		blame-1.16.5-3.6.1-forge.jar                      |Blame!                        |blame                         |1.16.5-3.6.1-forge  |DONE      |Manifest: NOSIGNATURE
		subwild-1.3.0.jar                                 |Subterranean Wilderness       |subwild                       |1.3.0               |DONE      |Manifest: NOSIGNATURE
		soulsandsmobs-beta0.4-1.16.4.jar                  |Soul Sands Mobs               |soul_sands_mobs               |0.3                 |DONE      |Manifest: NOSIGNATURE
		DynamicSurroundings-1.16.5-4.0.5.0.jar            |§3Dynamic Surroundings        |dsurround                     |4.0.5.0             |DONE      |Manifest: NOSIGNATURE
		DungeonsArise-1.16.5-2.1.47-release.jar           |When Dungeons Arise           |dungeons_arise                |2.1.47              |DONE      |Manifest: NOSIGNATURE
		forge-1.16.5-36.2.8-server.jar                    |Minecraft                     |minecraft                     |1.16.5              |DONE      |Manifest: NOSIGNATURE
		cofh_core-1.16.5-1.3.1.jar                        |CoFH Core                     |cofh_core                     |1.3.1               |DONE      |Manifest: NOSIGNATURE
		logprot-1.16-1.5.jar                              |Logprot                       |logprot                       |1.4                 |DONE      |Manifest: NOSIGNATURE
		physics-mod-1.3.4_forge.jar                       |Physics Mod                   |physicsmod                    |1.0                 |DONE      |Manifest: NOSIGNATURE
		pandoras_creatures-1.16.3-2.0.1.jar               |Pandoras Creatures            |pandoras_creatures            |1.16.3-2.0.1        |DONE      |Manifest: NOSIGNATURE
		Spheric 1.0.5 1.16.5.jar                          |Spheric                       |spheric                       |1.0.5               |DONE      |Manifest: NOSIGNATURE
		greekfantasy-16.5.3.jar                           |Greek Fantasy                 |greekfantasy                  |16.5.3              |DONE      |Manifest: NOSIGNATURE
		majrusz-library-1.16.4-2.0.1.jar                  |Majrusz Library               |majrusz_library               |2.0.1               |DONE      |Manifest: NOSIGNATURE
		flywheel-1.16-0.2.4.jar                           |Flywheel                      |flywheel                      |1.16-0.2.4          |DONE      |Manifest: NOSIGNATURE
		ftb-backups-2.1.1.6.jar                           |FTB Backups                   |ftbbackups                    |2.1.1.6             |DONE      |Manifest: NOSIGNATURE
		serverconfigupdater-1.3.jar                       |ServerConfig Updater          |serverconfigupdater           |1.3                 |DONE      |Manifest: NOSIGNATURE
		polymorph-forge-1.16.5-0.25.jar                   |Polymorph                     |polymorph                     |1.16.5-0.25         |DONE      |Manifest: NOSIGNATURE
		AutoRegLib-1.6-49.jar                             |AutoRegLib                    |autoreglib                    |1.6-49              |DONE      |Manifest: NOSIGNATURE
		WorldPreGenerator-1.16.5-2.0.0.jar                |World Pre Generator           |world_pre_generator           |2.0.0               |DONE      |Manifest: NOSIGNATURE
		evilwanderingtrader-1.2.jar                       |Evil Wandering Trader         |evilwanderingtrader           |1.2                 |DONE      |Manifest: NOSIGNATURE
		Regrowth-1.16.4-1.16.5-1.35.0.22.jar              |Regrowth Mod                  |regrowth                      |1.16.5-1.35.0.22    |DONE      |Manifest: NOSIGNATURE
		globaldataandresourcepacks-1.16.4-1.7.4.jar       |Global Data- & Resourcepacks  |globaldataandresourcepacks    |1.16.4-1.7.3        |DONE      |Manifest: NOSIGNATURE
		structurize-0.13.219-ALPHA-universal.jar          |Structurize                   |structurize                   |0.13.219-ALPHA      |DONE      |Manifest: NOSIGNATURE
		Wesley's Roguelike Dungeons (Version 1.0).jar     |Wesley's Roguelike Dungeons   |wrd                           |1.0.0               |DONE      |Manifest: NOSIGNATURE
		FastFurnace-1.16.4-4.4.0.jar                      |FastFurnace                   |fastfurnace                   |4.4.0               |DONE      |Manifest: NOSIGNATURE
		PuzzlesLib-v1.0.12-1.16.5.jar                     |Puzzles Lib                   |puzzleslib                    |1.0.12              |DONE      |Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		NefsMedievalPub+v9.8(1.16.5).jar                  |Nef Deco Mod                  |nefdecomod                    |0.9.8               |DONE      |Manifest: NOSIGNATURE
		byg-1.3.5.jar                                     |Oh The Biomes You'll Go       |byg                           |1.3.4               |DONE      |Manifest: NOSIGNATURE
		bettergolem-1.16.5-0.2.0.jar                      |Better Golem                  |bettergolem                   |1.16.5-0.2.0        |DONE      |Manifest: NOSIGNATURE
		Follow-Me-1.16.5-1.1.7a.jar                       |Follow Me                     |followme                      |1.1.7a              |DONE      |Manifest: NOSIGNATURE
		parrying-2.1.0.jar                                |Parrying                      |parrying                      |2.1.0               |DONE      |Manifest: NOSIGNATURE
		farlanders-1.16.4-1.3.9.jar                       |The Farlanders                |farlanders                    |1.3.9               |DONE      |Manifest: NOSIGNATURE
		StructuresPlusEnd.jar                             |Structure plus ii             |structure_plus_ii             |1.0.0               |DONE      |Manifest: NOSIGNATURE
		DungeonsMod-1.16.3-1.4.40.jar                     |Dungeons Mod                  |dungeonsmod                   |1.16.3-1.4.40       |DONE      |Manifest: NOSIGNATURE
		Instrumental-Mobs-1.16.5-1.3.3.jar                |Instrumental Mobs             |instrumentalmobs              |1.3.3               |DONE      |Manifest: NOSIGNATURE
		blue_skies-1.16.5-1.1.3.jar                       |Blue Skies                    |blue_skies                    |1.1.3               |DONE      |Manifest: NOSIGNATURE
		Piglin Expansion 1.0.jar                          |Piglin Expansion              |piglin_expansion              |1.0.0               |DONE      |Manifest: NOSIGNATURE
		tea_kettle-1.16.5-0.4.0.0.jar                     |Tea Kettle                    |tea_kettle                    |task ':jar' property|DONE      |Manifest: NOSIGNATURE
		Wyrmroost-1.16.3-1.2.11.jar                       |Wyrmroost                     |wyrmroost                     |1.16.3-1.2.11       |DONE      |Manifest: NOSIGNATURE
		eidolon-0.2.7.jar                                 |Eidolon                       |eidolon                       |0.2.7               |DONE      |Manifest: NOSIGNATURE
		incontrol-1.16-5.2.1.jar                          |InControl                     |incontrol                     |1.16-5.2.1          |DONE      |Manifest: NOSIGNATURE
		Ore Stone Variants-6.2.jar                        |Ore Stone Variants            |osv                           |6.2                 |DONE      |Manifest: NOSIGNATURE
		InsaneLib-1.3.1-mc1.16.5.jar                      |InsaneLib                     |insanelib                     |1.3.1-mc1.16.5      |DONE      |Manifest: NOSIGNATURE
		FFXIIMod-1.16.5-0.6.1.jar                         |Final Fantasy XII Mod         |ffxiimod                      |0.6.1               |DONE      |Manifest: NOSIGNATURE
		Controlling-7.0.0.27.jar                          |Controlling                   |controlling                   |7.0.0.27            |DONE      |Manifest: NOSIGNATURE
		Placebo-1.16.5-4.6.0.jar                          |Placebo                       |placebo                       |4.6.0               |DONE      |Manifest: NOSIGNATURE
		citadel-1.8.1-1.16.5.jar                          |Citadel                       |citadel                       |1.8.1               |DONE      |Manifest: NOSIGNATURE
		alexsmobs-1.12.1.jar                              |Alex's Mobs                   |alexsmobs                     |1.12.1              |DONE      |Manifest: NOSIGNATURE
		iceandfire-2.1.9-1.16.5.jar                       |Ice and Fire                  |iceandfire                    |2.1.9-1.16.5        |DONE      |Manifest: NOSIGNATURE
		customvillagertrades-1.16_V12.jar                 |Custom Villager Trades        |customvillagertrades          |1.16 v12            |DONE      |Manifest: NOSIGNATURE
		MutantBeasts-1.16.4-1.1.3.jar                     |Mutant Beasts                 |mutantbeasts                  |1.16.4-1.1.3        |DONE      |Manifest: d9:be:bd:b6:9a:e4:14:aa:05:67:fb:84:06:77:a0:c5:10:ec:27:15:1b:d6:c0:88:49:9a:ef:26:77:61:0b:5e
		Bookshelf-Forge-1.16.5-10.3.29.jar                |Bookshelf                     |bookshelf                     |10.3.29             |DONE      |Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		Tips-1.16.5-4.0.10.jar                            |Tips                          |tips                          |4.0.10              |DONE      |Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		sophisticatedbackpacks-1.16.5-3.8.1.384.jar       |Sophisticated Backpacks       |sophisticatedbackpacks        |1.16.5-3.8.1.384    |DONE      |Manifest: NOSIGNATURE
		ShretNether - Release -1.3.2.jar                  |Shret Nether                  |shretnether                   |1.0                 |DONE      |Manifest: NOSIGNATURE
		ProgressiveBosses-3.3.3-mc1.16.5.jar              |Progressive Bosses            |progressivebosses             |3.3.3               |DONE      |Manifest: NOSIGNATURE
		Ambience-1.16.5-1.0.0.jar                         |Ambience - Extras             |ambience                      |1.16.5-1.0.0        |DONE      |Manifest: NOSIGNATURE
		LostTrinkets-1.16.5-0.1.27.jar                    |Lost Trinkets                 |losttrinkets                  |0.1.27              |DONE      |Manifest: NOSIGNATURE
		oretweaker-1.1.1.jar                              |OreTweaker                    |oretweaker                    |1.1.1               |DONE      |Manifest: NOSIGNATURE
		chocolate-1.3.0-1.16.4.jar                        |Chocolate                     |chocolate                     |1.3.0-1.16.4        |DONE      |Manifest: NOSIGNATURE
		UndeadExpansion-1.16.5-2.0.0.jar                  |Undead Expansion              |undead_expansion              |1.0.1               |DONE      |Manifest: NOSIGNATURE
		FarmersDelight-1.16.5-0.5.1.jar                   |Farmer's Delight              |farmersdelight                |1.16.5-0.5.1        |DONE      |Manifest: NOSIGNATURE
		fd_cookbook-2.0.jar                               |Farmers Delight Cookbook      |fd_cookbook                   |2.0                 |DONE      |Manifest: NOSIGNATURE
		BloodAndMadness-1.16.5Forge-v1.1.13.jar           |Blood And Madness             |bloodandmadness               |1.0                 |DONE      |Manifest: NOSIGNATURE
		Ping-1.16.4-1.6.9.jar                             |Ping                          |ping                          |1.16.4-1.6.9        |DONE      |Manifest: NOSIGNATURE
		projectvibrantjourneys-1.16.5-3.2.10.jar          |Project: Vibrant Journeys     |projectvibrantjourneys        |1.16.5-3.2.10       |DONE      |Manifest: NOSIGNATURE
		EndRemastered-R36.jar                             |End Remastered 3.6            |endrem                        |1.16.3              |DONE      |Manifest: NOSIGNATURE
		Lollipop-1.16.5-3.2.9.jar                         |Lollipop                      |lollipop                      |3.2.9               |DONE      |Manifest: NOSIGNATURE
		rare-ice-0.2.2.jar                                |Rare Ice                      |rare-ice                      |version             |DONE      |Manifest: NOSIGNATURE
		dungeons_enhanced-1.16.5-1.3.jar                  |Dungeons Enhanced             |dungeons_enhanced             |1.3                 |DONE      |Manifest: NOSIGNATURE
		CNB-1.16.3_5-1.2.11.jar                           |Creatures and Beasts          |cnb                           |1.2.11              |DONE      |Manifest: NOSIGNATURE
		geckolib-forge-1.16.5-3.0.49.jar                  |GeckoLib                      |geckolib3                     |3.0.49              |DONE      |Manifest: NOSIGNATURE
		Wilds Version 2.8.jar                             |Wilds                         |wilds                         |1.0.0               |DONE      |Manifest: NOSIGNATURE
		Patchouli-1.16.4-53.2.jar                         |Patchouli                     |patchouli                     |1.16.4-53.2         |DONE      |Manifest: NOSIGNATURE
		Feywild-1.16.5-2.0.4.jar                          |Feywild                       |feywild                       |1.16.5-2.0.4        |DONE      |Manifest: NOSIGNATURE
		ars_nouveau-1.16.5-1.23.11.jar                    |Ars Nouveau                   |ars_nouveau                   |1.23.11             |DONE      |Manifest: NOSIGNATURE
		LurkerMod(FORGE-1.16.4) - 1.0.8.jar               |Lurker                        |lurkermod                     |1.16.4-1.0.8        |DONE      |Manifest: NOSIGNATURE
		betterbiomeblend-1.16.4-1.2.9-forge.jar           |Better Biome Blend            |betterbiomeblend              |1.16.4-1.2.9-forge  |DONE      |Manifest: NOSIGNATURE
		NoCube's_Sea_Dwellers_1.0.1.jar                   |NoCube's Sea Dwellers         |seadwellers                   |1.0.1               |DONE      |Manifest: NOSIGNATURE
		Desolation 1.1.0-1 1.16.5.jar                     |Desolation (Forge)            |desolation                    |1.1.0-1             |DONE      |Manifest: NOSIGNATURE
		architectury-1.14.157-forge.jar                   |Architectury                  |architectury                  |1.14.157            |DONE      |Manifest: NOSIGNATURE
		ftb-gui-library-1605.2.1.41-forge.jar             |FTB GUI Library               |ftbguilibrary                 |1605.2.1.41         |DONE      |Manifest: NOSIGNATURE
		ftb-teams-1604.1.0.16-forge.jar                   |FTB Teams                     |ftbteams                      |1604.1.0.16         |DONE      |Manifest: NOSIGNATURE
		AgeingSpawners-1.16.5-1.1.0.jar                   |Ageing Spawners               |ageingspawners                |1.1.0               |DONE      |Manifest: NOSIGNATURE
		ZenSummoning-1.16.4-1.3.1.jar                     |Zen Summoning                 |zensummoning                  |1.3.1               |DONE      |Manifest: NOSIGNATURE
		enchantwithmob-1.16.5-1.5.1.jar                   |Enchant With Mob              |enchantwithmob                |1.16.5-1.5.1        |DONE      |Manifest: NOSIGNATURE
		BetterAdvancements-1.16.5-0.1.1.115.jar           |Better Advancements           |betteradvancements            |0.1.1.115           |DONE      |Manifest: NOSIGNATURE
		spiders-2.0-1.16.4-1.0.4.jar                      |Spiders 2.0                   |spiderstpo                    |1.0.4               |DONE      |Manifest: NOSIGNATURE
		Shrines-1.16.5-1.8.1.jar                          |Shrines                       |shrines                       |1.16.5-1.8.1        |DONE      |Manifest: NOSIGNATURE
		item-filters-1605.2.4-build.30-forge.jar          |Item Filters                  |itemfilters                   |1605.2.4-build.30   |DONE      |Manifest: NOSIGNATURE
		ftb-quests-1605.2.1-build.39-forge.jar            |FTB Quests                    |ftbquests                     |1605.2.1-build.39   |DONE      |Manifest: NOSIGNATURE
		Druidcraft-1.16.5-0.4.52.jar                      |Druidcraft                    |druidcraft                    |0.4.52              |DONE      |Manifest: NOSIGNATURE
		the-conjurer-1.16.4-1.0.13.jar                    |The Conjurer                  |conjurer_illager              |1.0.13              |DONE      |Manifest: NOSIGNATURE
		dungeons_mobs-1.16.5-1.0.10.jar                   |Dungeons Mobs                 |dungeons_mobs                 |1.0.10              |DONE      |Manifest: NOSIGNATURE
		abnormals_core-1.16.5-3.3.0.jar                   |Abnormals Core                |abnormals_core                |3.3.0               |DONE      |Manifest: NOSIGNATURE
		upgrade_aquatic-1.16.5-3.1.0.jar                  |Upgrade Aquatic               |upgrade_aquatic               |3.1.0               |DONE      |Manifest: NOSIGNATURE
		Better-Badlands-1.16.5-2.0.3.jar                  |Better Badlands               |better_badlands               |1.16.5-2.0.3        |DONE      |Manifest: NOSIGNATURE
		endergetic-1.16.4-3.0.0.jar                       |The Endergetic Expansion      |endergetic                    |3.0.0               |DONE      |Manifest: NOSIGNATURE
		personality-1.16.5-1.0.2.jar                      |Personality                   |personality                   |1.0.2               |DONE      |Manifest: NOSIGNATURE
		savageandravage-1.16.5-3.1.0.jar                  |Savage & Ravage               |savageandravage               |3.1.0               |DONE      |Manifest: NOSIGNATURE
		autumnity-1.16.5-2.1.1.jar                        |Autumnity                     |autumnity                     |2.1.1               |DONE      |Manifest: NOSIGNATURE
		nethers_delight-2.1.jar                           |Nethers Delight               |nethers_delight               |2.1                 |DONE      |Manifest: NOSIGNATURE
		UNDEADv.1.1release.jar                            |UNDEAD                        |undead                        |2.0.0               |DONE      |Manifest: NOSIGNATURE
		toadterror-1.16.4-1.0.0.jar                       |Toad Terror                   |toadterror                    |1.0.0               |DONE      |Manifest: NOSIGNATURE
		ensorcellation-1.16.5-1.3.1.jar                   |Ensorcellation                |ensorcellation                |1.3.1               |DONE      |Manifest: 75:0b:cc:9b:64:2e:9b:c4:41:d1:95:00:71:ee:87:1a:b3:5e:4b:da:8e:e8:39:00:fd:5d:e5:9c:40:42:33:09
		create-mc1.16.5_v0.3.2f.jar                       |Create                        |create                        |v0.3.2f             |DONE      |Manifest: NOSIGNATURE
		Waystones_1.16.5-7.6.3.jar                        |Waystones                     |waystones                     |7.6.3               |DONE      |Manifest: NOSIGNATURE
		Clumps-6.0.0.27.jar                               |Clumps                        |clumps                        |6.0.0.27            |DONE      |Manifest: NOSIGNATURE
		tumbleweed-1.16-0.4.9.jar                         |Tumbleweed                    |tumbleweed                    |1.16-0.4.9          |DONE      |Manifest: NOSIGNATURE
		Artifacts-1.16.5-2.10.0.jar                       |Artifacts                     |artifacts                     |1.16.5-2.10.0       |DONE      |Manifest: NOSIGNATURE
		OuterEnd-0.2.14.jar                               |The Outer End                 |outer_end                     |0.2.9               |DONE      |Manifest: NOSIGNATURE
		DungeonCrawl-1.16.5-2.3.2.jar                     |Dungeon Crawl                 |dungeoncrawl                  |2.3.2               |DONE      |Manifest: NOSIGNATURE
		betteranimalsplus-1.16.5-10.2.0.jar               |Better Animals Plus           |betteranimalsplus             |10.2.0              |DONE      |Manifest: NOSIGNATURE
		BadMobs-1.16.5-9.0.3.jar                          |BadMobs                       |badmobs                       |9.0.3               |DONE      |Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		Nimble-1.16.2-0.3.1.jar                           |Nimble                        |nimble                        |NONE                |DONE      |Manifest: NOSIGNATURE
		lazydfu-0.1.3.jar                                 |LazyDFU                       |lazydfu                       |0.1.3               |DONE      |Manifest: NOSIGNATURE
		mahoutsukai-1.16.5-v1.33.0.jar                    |Mahou Tsukai                  |mahoutsukai                   |1.16.5-v1.33.0      |DONE      |Manifest: NOSIGNATURE
		farsight-1.7.jar                                  |Farsight mod                  |farsight_view                 |1.7                 |DONE      |Manifest: NOSIGNATURE
		ftb-chunks-1605.2.3-build.75.jar                  |FTB Chunks                    |ftbchunks                     |1605.2.3-build.75   |DONE      |Manifest: NOSIGNATURE
		RecipeStages-2.0.0.16.jar                         |Recipe Stages                 |recipestages                  |2.0.0.16            |DONE      |Manifest: NOSIGNATURE
		TravelersTitles-1.16.4-1.5.jar                    |Traveler's Titles             |travelerstitles               |1.16.4-1.5          |DONE      |Manifest: NOSIGNATURE
		meetyourfight-1.16.5-1.1.2.jar                    |Meet Your Fight               |meetyourfight                 |1.1.2               |DONE      |Manifest: NOSIGNATURE
		twist-1.4.1.jar                                   |Twist                         |twist                         |4.0.0               |DONE      |Manifest: NOSIGNATURE
		selene-1.16.5-1.8.0.jar                           |Selene                        |selene                        |1.16.5-1.0          |DONE      |Manifest: NOSIGNATURE
		EnchantmentDescriptions-1.16.5-7.0.12.jar         |EnchantmentDescriptions       |enchdesc                      |7.0.12              |DONE      |Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		Jade-1.16.4-2.8.0.jar                             |Jade                          |jade                          |2.8.0               |DONE      |Manifest: NOSIGNATURE
		CreativeCore_v2.2.1_mc1.16.5.jar                  |CreativeCore                  |creativecore                  |2.0.0               |DONE      |Manifest: NOSIGNATURE
		towers_of_the_wild-1.16.3-2.1.0.1.jar             |Towers Of The Wild            |towers_of_the_wild            |1.16.3-2.1.0        |DONE      |Manifest: NOSIGNATURE
		smoothboot-forge-1.16.4-1.2.2.jar                 |Smooth Boot                   |smoothboot                    |1.16.4-1.2.2        |DONE      |Manifest: NOSIGNATURE
		atmospheric-1.16.5-3.1.0.jar                      |Atmospheric                   |atmospheric                   |3.1.0               |DONE      |Manifest: NOSIGNATURE
		Iceberg-1.16.5-1.0.11.jar                         |Iceberg                       |iceberg                       |1.0.11              |DONE      |Manifest: NOSIGNATURE
		Quark-r2.4-319.jar                                |Quark                         |quark                         |r2.4-319            |DONE      |Manifest: NOSIGNATURE
		charm-forge-1.16.5-2.3.2.jar                      |Charm                         |charm                         |2.3.2               |DONE      |Manifest: NOSIGNATURE
		DeeperNetherBiomes-v2.0.2-1.16.5.jar              |Deeper Nether Biomes          |deepernetherbiomes            |2.0.0               |DONE      |Manifest: NOSIGNATURE
		adaptive_performance_tweaks_1.16.5-1.1.4.jar      |Adaptive Performance Tweaks   |adaptive_performance_tweaks   |1.1.4               |DONE      |Manifest: NOSIGNATURE
		abnormals_delight-1.16.5-1.2.0.jar                |Abnormals Delight             |abnormals_delight             |1.2.0               |DONE      |Manifest: NOSIGNATURE
		StorageDrawers-1.16.3-8.3.0.jar                   |Storage Drawers               |storagedrawers                |8.3.0               |DONE      |Manifest: NOSIGNATURE
		performant-1.16.2-5-3.72m.jar                     |Performant                    |performant                    |3.56m               |DONE      |Manifest: NOSIGNATURE
		twoplayersonehorse-1.16.4-2.0.2.jar               |2 players 1 horse             |twoplayersonehorse            |1.16.4-2.0.2        |DONE      |Manifest: NOSIGNATURE
		InventoryHud_[1.16.2-1.16.5].forge-3.4.1.jar      |Inventory HUD+(Forge edition) |inventoryhud                  |3.4.1               |DONE      |Manifest: NOSIGNATURE
		minecolonies-1.0.0-RELEASE-universal.jar          |MineColonies                  |minecolonies                  |1.0.0-RELEASE       |DONE      |Manifest: NOSIGNATURE
		workshopsofdoom-1.16.4-1.1.0.1.jar                |Workshops of Doom             |workshopsofdoom               |1.1.0.1             |DONE      |Manifest: NOSIGNATURE
		HunterIllager-1.16.5-1.4.0.jar                    |Hunter Illager                |hunterillager                 |1.16.5-1.4.0        |DONE      |Manifest: NOSIGNATURE
		[BETA]dannys_expansion1.16.5-1.0.9.1.jar          |Danny's Expansion             |dannys_expansion              |1.0.9               |DONE      |Manifest: NOSIGNATURE
		mamt-1.16.5-1.8.0.jar                             |Mineshafts and Monsters Modpac|mamt                          |1.8.0               |DONE      |Manifest: NOSIGNATURE
		ferritecore-2.1.0-forge.jar                       |Ferrite Core                  |ferritecore                   |2.1.0               |DONE      |Manifest: 41:ce:50:66:d1:a0:05:ce:a1:0e:02:85:9b:46:64:e0:bf:2e:cf:60:30:9a:fe:0c:27:e0:63:66:9a:84:ce:8a
		illagers_plus-1.16.4v1.7.2.jar                    |Illagers+                     |illagers_plus                 |1.16.4v1.7.2        |DONE      |Manifest: NOSIGNATURE
		improvedmobs-1.16.5-1.7.9.jar                     |Improved Mobs Mod             |improvedmobs                  |1.16.5-1.7.9        |DONE      |Manifest: NOSIGNATURE
		expandability-2.0.1-forge.jar                     |ExpandAbility                 |expandability                 |2.0.1               |DONE      |Manifest: NOSIGNATURE
		valhelsia_core-16.0.13a.jar                       |Valhelsia Core                |valhelsia_core                |16.0.13a            |DONE      |Manifest: NOSIGNATURE
		valhelsia_structures-1.16.5-0.1.6.jar             |Valhelsia Structures          |valhelsia_structures          |1.16.5-0.1.6        |DONE      |Manifest: NOSIGNATURE
		FabricBiomeApiReforged-1.0.5.jar                  |Fabric BiomeApi Reforged      |fabric-biome-api              |1.0.5               |DONE      |Manifest: NOSIGNATURE
	Crash Report UUID: ac3a9466-cae4-4d1f-8de2-a22e9646cb5e
	Kiwi Modules: 
		kiwi:contributors
		kiwi:data
		snowrealmagic:core
		snowrealmagic:world
	Player Count: 1 / 72; [ServerPlayerEntity['Takemaroo'/437387, l='ServerLevel[Mineham]', x=-556.47, y=64.00, z=-967.39]]
	Data Packs: vanilla, mod:betterdungeons, mod:bigbrain, mod:infernalexp (incompatible), mod:elenaidodge, mod:nethers_exoticism, mod:betternether, mod:stalwart_dungeons, mod:strawgolem, mod:looot, mod:bettercaves (incompatible), mod:farmersdelightintegrations, mod:yungsapi, mod:pyromancer, mod:xreliquary, mod:lootbeams, mod:guardvillagers, mod:randompatches, mod:apotheosis (incompatible), mod:hornets, mod:snowrealmagic, mod:jeresources, mod:paraglider, mod:revampedwolf, mod:supplementaries, mod:structure_gel, mod:corpse, mod:advancementplaques, mod:castle_in_the_sky, mod:tenshilib (incompatible), mod:cleancut (incompatible), mod:morevillagers, mod:biomesoplenty, mod:geode, mod:dungeons_plus, mod:simplyimprovedterrain, mod:extcaves, mod:betterdefaultbiomes, mod:highlighter, mod:spark, mod:riskofrainmod, mod:curios, mod:levelhearts (incompatible), mod:specialai, mod:rotten_piglins, mod:yungsextras, mod:mushroomquest, mod:knights, mod:obfuscate (incompatible), mod:atlaslib, mod:majruszs_difficulty, mod:sapience, mod:pmmo (incompatible), mod:mutantmore, mod:netherskeletons, mod:forestcraft, mod:cloth-config (incompatible), mod:toms_storage (incompatible), mod:customstartinggear (incompatible), mod:exoticbirds, mod:bettermineshafts, mod:tree_felling, mod:dungeons_gear, mod:kiwi, mod:betteranimationscollection, mod:mowziesmobs (incompatible), mod:jei, mod:enderlinginvaders, mod:comfortable_nether, mod:seals (incompatible), mod:kobolds, mod:passablefoliage, mod:harderbranchmining, mod:naturescompass (incompatible), mod:untamedwilds (incompatible), mod:libx, mod:stoneholm, mod:upstream, mod:champions (incompatible), mod:snowundertrees, mod:sulfuric, mod:jeitweaker, mod:crafttweaker, mod:gamestages, mod:restored_earth (incompatible), mod:forge, mod:offhandcombat (incompatible), mod:blame, mod:subwild, mod:soul_sands_mobs, mod:dsurround, mod:dungeons_arise, mod:cofh_core (incompatible), mod:logprot (incompatible), mod:physicsmod, mod:pandoras_creatures (incompatible), mod:spheric, mod:greekfantasy, mod:majrusz_library, mod:flywheel, mod:ftbbackups (incompatible), mod:serverconfigupdater (incompatible), mod:polymorph, mod:autoreglib (incompatible), mod:world_pre_generator, mod:evilwanderingtrader, mod:regrowth, mod:globaldataandresourcepacks (incompatible), mod:structurize, mod:wrd, mod:fastfurnace (incompatible), mod:puzzleslib, mod:nefdecomod, mod:byg, mod:bettergolem, mod:followme, mod:parrying, mod:farlanders (incompatible), mod:structure_plus_ii, mod:dungeonsmod (incompatible), mod:instrumentalmobs, mod:blue_skies (incompatible), mod:piglin_expansion, mod:tea_kettle, mod:wyrmroost (incompatible), mod:eidolon, mod:incontrol (incompatible), mod:osv (incompatible), mod:insanelib, mod:ffxiimod, mod:controlling, mod:placebo (incompatible), mod:citadel (incompatible), mod:alexsmobs, mod:iceandfire (incompatible), mod:customvillagertrades, mod:mutantbeasts (incompatible), mod:bookshelf, mod:tips, mod:sophisticatedbackpacks, mod:shretnether, mod:progressivebosses, mod:ambience, mod:losttrinkets, mod:oretweaker, mod:chocolate, mod:undead_expansion, mod:farmersdelight, mod:fd_cookbook, mod:bloodandmadness, mod:ping, mod:projectvibrantjourneys, mod:endrem, mod:lollipop, mod:rare-ice (incompatible), mod:dungeons_enhanced, mod:cnb, mod:geckolib3 (incompatible), mod:wilds, mod:patchouli (incompatible), mod:feywild, mod:ars_nouveau, mod:lurkermod (incompatible), mod:betterbiomeblend, mod:seadwellers, mod:desolation, mod:architectury, mod:ftbguilibrary (incompatible), mod:ftbteams (incompatible), mod:ageingspawners, mod:zensummoning (incompatible), mod:enchantwithmob, mod:betteradvancements, mod:spiderstpo, mod:shrines (incompatible), mod:itemfilters, mod:ftbquests, mod:druidcraft (incompatible), mod:conjurer_illager (incompatible), mod:dungeons_mobs (incompatible), mod:abnormals_core, mod:upgrade_aquatic, mod:better_badlands, mod:endergetic, mod:personality, mod:savageandravage, mod:autumnity, mod:nethers_delight, mod:undead, mod:toadterror (incompatible), mod:ensorcellation (incompatible), mod:create, mod:waystones (incompatible), mod:clumps, mod:tumbleweed (incompatible), mod:artifacts, mod:outer_end, mod:dungeoncrawl, mod:betteranimalsplus (incompatible), mod:badmobs (incompatible), mod:nimble, mod:lazydfu, mod:mahoutsukai (incompatible), mod:farsight_view, mod:ftbchunks, mod:recipestages, mod:travelerstitles, mod:meetyourfight (incompatible), mod:twist, mod:selene, mod:enchdesc, mod:jade, mod:creativecore, mod:towers_of_the_wild, mod:smoothboot, mod:atmospheric, mod:iceberg, mod:quark (incompatible), mod:charm, mod:deepernetherbiomes, mod:adaptive_performance_tweaks, mod:abnormals_delight, mod:storagedrawers (incompatible), mod:performant (incompatible), mod:twoplayersonehorse, mod:inventoryhud, mod:minecolonies (incompatible), mod:workshopsofdoom, mod:hunterillager, mod:dannys_expansion, mod:mamt, mod:ferritecore (incompatible), mod:illagers_plus, mod:improvedmobs (incompatible), mod:expandability, mod:valhelsia_core, mod:valhelsia_structures, mod:fabric-biome-api, file/MnM_Datapack, file/More_Bosses_v0.8.0_Dev_Datapack.zip, file/Pig_Boss_by_Spartakus_PSP_v_1.3.zip, file/Ships v11 for [1.16.5], file/desert-pyramid-boss-unzip-me, file/hard-ender-dragon-ex-1-16-2-5.zip, file/illager-fortresses-v8-for-1-16-5.zip, file/pillager-stronghold.zip, file/the-forbidden-castle-v1-1.zip, resources
	Is Modded: Definitely; Server brand changed to 'forge'
	Type: Dedicated Server (map_server.txt)
