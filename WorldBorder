//for minus border use negative ones
plusxborder = 10
minusxborder = -10
pluszborder = 10
minuszborder = -10 

mc.listen('onMove',function(pl){
    let ppos = pl.pos
    if (ppos.x > plusxborder ){
        pl.tell(Format.Red + 'World Border',5)
        pl.teleport(plusxborder,ppos.y,ppos.z,ppos.dimid)
    }
    if (ppos.z > pluszborder) {
        pl.tell(Format.Red + 'World Border',5)
        pl.teleport(ppos.x,ppos.y,pluszborder,ppos.dimid)
    }
    if (ppos.x < minusxborder ){
        pl.tell(Format.Red + 'World Border',5)
        pl.teleport(minusxborder,ppos.y,ppos.z,ppos.dimid)
    }
    if (ppos.z < minuszborder) {
        pl.tell(Format.Red + 'World Border',5)
        pl.teleport(ppos.x,ppos.y,minuszborder,ppos.dimid)
    }

})

