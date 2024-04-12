<template>
  <div class="card">
    <div class="card-header pb-0">
      <h6>Inventory Table</h6>
    </div>
    <div class="card-body px-0 pt-0 pb-2">
      <div class="table-responsive p-0">
        <table class="table align-items-center mb-0">
          <thead>
            <tr>
              <th
                class="text-uppercase text-secondary text-xxs font-weight-bolder opacity-7"
              >
                Item Name/Description
              </th>
              <th
                class="text-uppercase text-secondary text-xxs font-weight-bolder opacity-7 ps-2"
              >
                ITEM CODE
              </th>
              <th
                class="text-center text-uppercase text-secondary text-xxs font-weight-bolder opacity-7"
              >
                Wholesale Price
              </th>
              <th
                class="text-center text-uppercase text-secondary text-xxs font-weight-bolder opacity-7"
              >
                Suggested Retail Price
              </th>
              <th
                class="text-center text-uppercase text-secondary text-xxs font-weight-bolder opacity-7"
              >
                Quantity
              </th>
              <th class="text-center text-uppercase text-secondary text-xxs font-weight-bolder opacity-7">
                Date Received
              </th>
              <th class="text-center text-uppercase text-secondary text-xxs font-weight-bolder opacity-7">
               Location
              </th>
              <th class="text-center text-uppercase text-secondary text-xxs font-weight-bolder opacity-7">
                Remarks
              </th>
              <th class="text-secondary opacity-7"></th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>
                <div class="d-flex px-2 py-1">
                  <div>
                    <img
                      src="../../assets/img/icons/inventory/apple-iphone12-pro-max.png"
                      class="avatar avatar-sm me-3"
                      alt="item1"
                    />
                  </div>
                  <div class="d-flex flex-column justify-content-center">
                    <h6 class="mb-0 text-sm">iPhone 12 Pro Max</h6>
                    <p class="text-xs text-secondary mb-0">
                      Apple Computer Inc. 
                    </p>
                  </div>
                </div>
              </td>
              <td>
                <span class="badge badge-sm bg-gradient-success">001</span>
              </td>
              <td class="align-middle text-center text-sm">
                <span class="badge badge-sm bg-gradient-success">PHP 69,999.00</span>
              </td>
              <td class="align-middle text-center text-sm">
                <span class="badge badge-sm bg-gradient-success">PHP 79,999.00</span>
              </td>
              <td class="align-middle text-center">
                <span class="text-secondary text-xs font-weight-bold"
                  >499</span
                >
              </td>
               <td class="align-middle text-center">
               <span class="text-secondary text-xs font-weight-bold">2024-04-10</span>
                </td>
               <td class="align-middle text-center">
               <span class="text-secondary text-xs font-weight-bold">Warehouse A</span> 
            </td>
            </tr>
            <tr>
              <td>
                <div class="d-flex px-2 py-1">
                  <div>
                    <img
                      src="../../assets/img/icons/inventory/borealis-backpack-northface.png"
                      class="avatar avatar-sm me-3"
                      alt="item2"
                    />
                  </div>
                  <div class="d-flex flex-column justify-content-center">
                    <h6 class="mb-0 text-sm">Borealis Backpack</h6>
                    <p class="text-xs text-secondary mb-0">
                      The North Face Apparel Corp.
                    </p>
                  </div>
                </div>
              </td>
              <td>
                <span class="badge badge-sm bg-gradient-success">002</span>
              </td>
              <td class="align-middle text-center text-sm">
                <span class="badge badge-sm bg-gradient-success">PHP 4,999.00</span>
              </td>
              <td class="align-middle text-center text-sm">
                <span class="badge badge-sm bg-gradient-success">PHP 4,999.00</span>
              </td>
              <td class="align-middle text-center">
                <span class="text-secondary text-xs font-weight-bold"
                  >999</span
                >
              </td>
              <td class="align-middle text-center">
                <span class="text-secondary text-xs font-weight-bold">2024-04-10</span>
              </td>
              <td class="align-middle text-center">
                <span class="text-secondary text-xs font-weight-bold">Warehouse B</span> 
              </td>
            </tr>
            <tr>
              <td>
                <div class="d-flex px-2 py-1">
                  <div>
                    <img
                      src="../../assets/img/icons/inventory/samsung-qled-55.png"
                      class="avatar avatar-sm me-3"
                      alt="item3"
                    />
                  </div>
                  <div class="d-flex flex-column justify-content-center">
                    <h6 class="mb-0 text-sm">Samsung 55-Inch QLED 4K Smart TV</h6>
                    <p class="text-xs text-secondary mb-0">
                      Samsung Electronics Co., Ltd.
                    </p>
                  </div>
                </div>
              </td>
              <td>
                <span class="badge badge-sm bg-gradient-success">003</span>               
              </td>
              <td class="align-middle text-center text-sm">
                <span class="badge badge-sm bg-gradient-success">₱56,999.00</span>
              </td>
              <td class="align-middle text-center text-sm">
                <span class="badge badge-sm bg-gradient-success">₱56,999.00</span>
              </td>
              <td class="align-middle text-center">
                <span class="text-secondary text-xs font-weight-bold"
                  >250</span
                >
              </td>
              <td class="align-middle text-center">
                <span class="text-secondary text-xs font-weight-bold">2024-04-10</span>
              </td>
              <td class="align-middle text-center">
                <span class="text-secondary text-xs font-weight-bold">Warehouse C</span>
              </td>
            </tr>
            <tr>
              <td>
                <div class="d-flex px-2 py-1">
                  <div>
                    <img
                      src="../../assets/img/icons/inventory/nike-air-pegasus-running-shoes.png"
                      class="avatar avatar-sm me-3"
                      alt="item4"
                    />
                  </div>
                  <div class="d-flex flex-column justify-content-center">
                    <h6 class="mb-0 text-sm">Nike Air Zoom Pegasus 38 Running Shoes</h6>
                    <p class="text-xs text-secondary mb-0">
                      Nike, Inc.
                    </p>
                  </div>
                </div>
              </td>
              <td>
                <span class="badge badge-sm bg-gradient-success">004</span>               
              </td>
              <td class="align-middle text-center text-sm">
                <span class="badge badge-sm bg-gradient-success">₱3,699.00</span>  
              </td>
              <td class="align-middle text-center text-sm">
                <span class="badge badge-sm bg-gradient-success">₱3,699.00</span>  
              </td>
              <td class="align-middle text-center">
                <span class="text-secondary text-xs font-weight-bold"
                  >799</span
                >
              </td>
              <td class="align-middle text-center">
                <span class="text-secondary text-xs font-weight-bold">2024-04-10</span>
              </td>
              <td class="align-middle text-center">
                <span class="text-secondary text-xs font-weight-bold">Warehouse D</span>
              </td>
            </tr>
            <tr>
              <td>
                <div class="d-flex px-2 py-1">
                  <div>
                    <img
                      src="../../assets/img/icons/inventory/kitchenaid-standmixer.png"
                      class="avatar avatar-sm me-3"
                      alt="item5"
                    />
                  </div>
                  <div class="d-flex flex-column justify-content-center">
                    <h6 class="mb-0 text-sm">KitchenAid Artisan Stand Mixer</h6>
                    <p class="text-xs text-secondary mb-0">
                      Whirlpool Corporation
                    </p>
                  </div>
                </div>
              </td>
              <td>
                <span class="badge badge-sm bg-gradient-success">005</span>  
              </td>
              <td class="align-middle text-center text-sm">
                <span class="badge badge-sm bg-gradient-success">₱26,995.00</span>  
              </td>
              <td class="align-middle text-center text-sm">
                <span class="badge badge-sm bg-gradient-success">₱26,995.00</span> 
              </td>
              <td class="align-middle text-center">
                <span class="text-secondary text-xs font-weight-bold"
                  >500</span
                >
              </td>
              <td class="align-middle text-center">
                <span class="text-secondary text-xs font-weight-bold">2024-04-10</span>
              </td>
              <td class="align-middle text-center">
                <span class="text-secondary text-xs font-weight-bold">Warehouse E</span>
              </td>
            </tr>
            <tr>
              <td>
                <div class="d-flex px-2 py-1">
                  <div>
                    <img
                      src="../../assets/img/icons/inventory/ikea-hemnes-drawer.png"
                      class="avatar avatar-sm me-3"
                      alt="item5"
                    />
                  </div>
                  <div class="d-flex flex-column justify-content-center">
                    <h6 class="mb-0 text-sm">IKEA Hemnes 8-Drawer Dresser</h6>
                    <p class="text-xs text-secondary mb-0">
                      Inter IKEA Systems B.V.
                    </p>
                  </div>
                </div>
              </td>
              <td>
                <span class="badge badge-sm bg-gradient-success">006</span>  
              </td>
              <td class="align-middle text-center text-sm">
                <span class="badge badge-sm bg-gradient-success">₱26,995.00</span> 
              </td>
              <td class="align-middle text-center text-sm">
                <span class="badge badge-sm bg-gradient-success">₱26,995.00</span>
              </td>
              <td class="align-middle text-center">
                <span class="text-secondary text-xs font-weight-bold"
                  >499</span
                >
              </td>
              <td class="align-middle text-center">
                <span class="text-secondary text-xs font-weight-bold">2024-04-10</span>
              </td>
              <td class="align-middle text-center">
                <span class="text-secondary text-xs font-weight-bold">Warehouse F</span>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</template>
