main: com.massivecraft.factions.Factions
name: Factions
version: 2.8.2
website: http://massivecraft.com/factions
authors: [Cayorion, Brettflan]
description: §eFactions allows the players to team up and claim land as their own and start wars with other factions. This way we hope to inspire politics, intrigue, and team spirit. §aCayorion §efrom the minecraft server §aMassiveCraft §eis the lead Factions programmer. Feel free to visit us at §bhttp://massivecraft.com
depend: [MassiveCore]
softdepend: [PermissionsEx, Permissions, Essentials, EssentialsChat, HeroChat, iChat, LocalAreaChat, LWC, nChat, ChatManager, AuthMe, Vault, Spout, WorldEdit, WorldGuard, AuthDB, CaptureThePoints, CombatTag]
permissions:
# -------------------------------------------- #
# THE REAL NODES
# -------------------------------------------- #
  factions.access: {description: manage access, with the proper fperm, default: false}
  factions.access.faction: {description: grant faction access, with the proper fperm, default: false}
  factions.access.player: {description: grant player access, with the proper fperm, default: false}
  factions.access.view: {description: view access, default: false}
  factions.admin: {description: enable adminmode, default: false}
  factions.claim: {description: claim faction territory, default: false}
  factions.claim.one: {description: claim a single chunk, default: false}
  factions.claim.auto: {description: claim as you walk around, default: false}
  factions.claim.fill: {description: claim by filling, default: false}
  factions.claim.square: {description: claim by square and radius, default: false}
  factions.claim.circle: {description: claim by circle and radius, default: false}
  factions.claim.all: {description: claim all faction land, default: false}
  factions.create: {description: create new faction, default: false}
  factions.description: {description: change faction description, default: false}
  factions.disband: {description: disband faction, default: false}
  factions.expansions: {description: list expansions, default: false}
  factions.faction: {description: show faction information, default: false}
  factions.flag: {description: manage faction flags, default: false}
  factions.flag.list: {description: list flags, default: false}
  factions.flag.set: {description: set flags, default: false}
  factions.flag.show: {description: show flags, default: false}
  factions.home: {description: teleport to faction home, default: false}
  factions.invite: {description: manage invites, default: false}
  factions.invite.list: {description: list invited players, default: false}
  factions.invite.list.other: {description: list invited players of another factions, default: false}
  factions.invite.add: {description: invite player, default: false}
  factions.invite.remove: {description: revoke an invite, default: false}
  factions.join: {description: join faction, default: false}
  factions.join.any: {description: join closed faction, default: false}
  factions.join.others: {description: have another player join faction, default: false}
  factions.kick: {description: kick player from faction, default: false}
  factions.leave: {description: leave your faction, default: false}
  factions.list: {description: list all factions, default: false}
  factions.map: {description: show territory map, default: false}
  factions.money: {description: manage faction money, default: false}
  factions.money.balance: {description: show faction money, default: false}
  factions.money.balance.any: {description: show another factions money, default: false}
  factions.money.deposit: {description: deposit to faction, default: false}
  factions.money.f2f: {description: transfer f --> f, default: false}
  factions.money.f2p: {description: transfer f --> p, default: false}
  factions.money.p2f: {description: transfer p --> f, default: false}
  factions.money.withdraw: {description: withdraw from faction, default: false}
  factions.motd: {description: faction motd, default: false}
  factions.open: {description: set if invitation is required to join, default: false}
  factions.perm: {description: change faction permissions, default: false}
  factions.perm.list: {description: list perms, default: false}
  factions.perm.set: {description: set perms, default: false}
  factions.perm.show: {description: show perms, default: false}
  factions.player: {description: show player information}
  factions.powerboost: {description: set powerboost, default: false}
  factions.rank: {description: manage/show ranks, default: false}
  factions.rank.show: {description: show rank, default: false}
  factions.rank.action: {description: change rank, default: false}
  factions.relation: {description: set relation wish to another faction, default: false}
  factions.seechunk: {description: see the chunk you stand in, default: false}
  factions.seechunkold: {description: see the chunk you stand in, default: false}
  factions.sethome: {description: set the faction home, default: false}
  factions.setpower: {description: set power, default: false}
  factions.status: {description: show faction status, default: false}
  factions.name: {description: set faction name, default: false}
  factions.title: {description: set player title, default: false}
  factions.title.color: {description: set player title with color, default: false}
  factions.territorytitles: {description: toggle territory titles, default: false}
  factions.unclaim: {description: unclaim faction territory, default: false}
  factions.unclaim.one: {description: unclaim a single chunk, default: false}
  factions.unclaim.auto: {description: unclaim as you walk around, default: false}
  factions.unclaim.fill: {description: unclaim by filling, default: false}
  factions.unclaim.square: {description: unclaim by square and radius, default: false}
  factions.unclaim.circle: {description: unclaim by circle and radius, default: false}
  factions.unclaim.all: {description: unclaim all faction land, default: false}
  factions.unsethome: {description: unset faction home, default: false}
  factions.unstuck: {description: teleport to nearest wilderness, default: false}
  factions.version: {description: see plugin version, default: false}
# -------------------------------------------- #
# STAR NOTATION
# -------------------------------------------- #
  factions.*:
    children:
      factions.access: true
      factions.access.faction: true
      factions.access.player: true
      factions.access.view: true
      factions.admin: true
      factions.claim: true
      factions.claim.one: true
      factions.claim.auto: true
      factions.claim.fill: true
      factions.claim.square: true
      factions.claim.circle: true
      factions.claim.all: true
      factions.create: true
      factions.demote: true
      factions.description: true
      factions.disband: true
      factions.expansions: true
      factions.faction: true
      factions.flag: true
      factions.flag.list: true
      factions.flag.set: true
      factions.flag.show: true
      factions.home: true
      factions.invite: true
      factions.invite.list: true
      factions.invite.list.other: true
      factions.invite.add: true
      factions.invite.remove: true
      factions.join: true
      factions.join.any: true
      factions.join.others: true
      factions.kick: true
      factions.leader: true
      factions.leader.any: true
      factions.leave: true
      factions.list: true
      factions.map: true
      factions.money: true
      factions.money.balance: true
      factions.money.balance.any: true
      factions.money.deposit: true
      factions.money.f2f: true
      factions.money.f2p: true
      factions.money.p2f: true
      factions.money.withdraw: true
      factions.motd: true
      factions.officer: true
      factions.officer.any: true
      factions.open: true
      factions.perm: true
      factions.perm.list: true
      factions.perm.set: true
      factions.perm.show: true
      factions.player: true
      factions.powerboost: true
      factions.promote: true
      factions.relation: true
      factions.seechunk: true
      factions.seechunkold: true
      factions.sethome: true
      factions.setpower: true
      factions.status: true
      factions.name: true
      factions.title: true
      factions.title.color: true
      factions.territorytitles: true
      factions.unclaim: true
      factions.unclaim.one: true
      factions.unclaim.auto: true
      factions.unclaim.fill: true
      factions.unclaim.square: true
      factions.unclaim.circle: true
      factions.unclaim.all: true
      factions.unsethome: true
      factions.unstuck: true
      factions.version: true
# -------------------------------------------- #
# KITS
# -------------------------------------------- #
  factions.kit.op:
    default: op
    children:
      factions.*: true
  factions.kit.rank3:
    default: false
    children:
      factions.kit.rank2: true
  factions.kit.rank2:
    default: false
    children:
      factions.kit.rank1: true
      factions.powerboost: true
      factions.join.any: true
      factions.join.others: true
      factions.leader.any: true
      factions.officer.any: true
      factions.access.any: true
      factions.setpower: true
  factions.kit.rank1:
    default: false
    children:
      factions.kit.rank0: true
      factions.admin: true
      factions.invite.list.other: true
  factions.kit.rank0:
    default: false
    children:
      factions.access: true
      factions.access.faction: true
      factions.access.player: true
      factions.access.view: true
      factions.claim: true
      factions.claim.one: true
      factions.claim.auto: true
      factions.claim.fill: true
      factions.claim.square: true
      factions.claim.circle: true
      factions.claim.all: true
      factions.create: true
      factions.demote: true
      factions.description: true
      factions.disband: true
      factions.expansions: true
      factions.faction: true
      factions.flag: true
      factions.flag.list: true
      factions.flag.set: true
      factions.flag.show: true
      factions.home: true
      factions.invite: true
      factions.invite.list: true
      factions.invite.add: true
      factions.invite.remove: true
      factions.join: true
      factions.kick: true
      factions.leader: true
      factions.leave: true
      factions.list: true
      factions.map: true
      factions.money: true
      factions.money.balance: true
      factions.money.balance.any: true
      factions.money.deposit: true
      factions.money.f2f: true
      factions.money.f2p: true
      factions.money.p2f: true
      factions.money.withdraw: true
      factions.motd: true
      factions.officer: true
      factions.open: true
      factions.perm: true
      factions.perm.list: true
      factions.perm.set: true
      factions.perm.show: true
      factions.player: true
      factions.promote: true
      factions.rank: true
      factions.rank.show: true
      factions.rank.action: true
      factions.relation: true
      factions.seechunk: true
      factions.seechunkold: true
      factions.sethome: true
      factions.status: true
      factions.name: true
      factions.title: true
      factions.title.color: true
      factions.territorytitles: true
      factions.unclaim: true
      factions.unclaim.one: true
      factions.unclaim.auto: true
      factions.unclaim.fill: true
      factions.unclaim.square: true
      factions.unclaim.circle: true
      factions.unclaim.all: true
      factions.unsethome: true
      factions.unstuck: true
      factions.version: true
  factions.kit.default:
    default: true
    children:
