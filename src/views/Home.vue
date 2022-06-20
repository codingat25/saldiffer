<template>
  <section id="calculator">
    <div class="overflow-auto rounded-lg">
      <table class="w-full flex md:block">
        <thead class="bg-blue-300 border-b-2 border-gray-200">
          <tr class="flex flex-col md:flex-row">
            <th class="p-2 text-sm tracking-normal text-center">No.</th>
            <th class="p-2 text-sm tracking-normal text-center">Employee Number</th>
            <th class="p-2 text-sm tracking-normal text-center">Last Name</th>
            <th class="p-2 text-sm tracking-normal text-center">First Name</th>
            <th class="p-2 text-sm tracking-normal text-center">Middle Initial</th>
            <th class="p-2 text-sm tracking-normal text-center">Position</th>
            <th class="p-2 text-sm tracking-normal text-center">Date of Last Promotion</th>
            <th class="p-2 text-sm tracking-normal text-center">Current Salary</th>
            <th class="p-2 text-sm tracking-normal text-center">Actual Salary</th>
            <th class="p-2 text-sm tracking-normal text-center">Difference (Current - Actual)</th>
            <th class="p-2 text-sm tracking-normal text-center">Period Covered (From)</th>
            <th class="p-2 text-sm tracking-normal text-center">Period Covered (To)</th>
            <th class="p-2 text-sm tracking-normal text-center">Salary Differential</th>
            <th class="p-2 text-sm tracking-normal text-center">SD Bonus</th>
            <th class="p-2 text-sm tracking-normal text-center">Gross Amount</th>
            <th class="p-2 text-sm tracking-normal text-center">GSIS</th>
            <th class="p-2 text-sm tracking-normal text-center">Less GSIS</th>
            <th class="p-2 text-sm tracking-normal text-center">Witholding Tax</th>
            <th class="p-2 text-sm tracking-normal text-center">Total Deductions</th>
            <th class="p-2 text-sm tracking-normal text-center">Net Amount</th>
          </tr>
        </thead>

        <tbody class="flex md:block">
          <tr class="flex flex-col md:flex-row bg-blue-100">
            <td class="p-2 text-sm tracking-normal text-center">1</td>
            <td class="p-2 text-sm tracking-normal text-center">4137497</td>
            <td class="p-2 text-sm tracking-normal text-center">MASANGYA</td>
            <td class="p-2 text-sm tracking-normal text-center">ALLYN</td>
            <td class="p-2 text-sm tracking-normal text-center">I</td>
            <td class="p-2 text-sm tracking-normal text-center">T III</td>
            <td class="p-2 text-sm tracking-normal text-center">6/26/2006</td>
            <td class="p-2 text-sm tracking-normal text-center">29,550.00</td>
            <td class="p-2 text-sm tracking-normal text-center">29,878.00</td>
            <td class="p-2 text-sm tracking-normal text-center">328.00</td>
            <td class="p-2 text-sm tracking-normal text-center">10/1/2021</td>
            <td class="p-2 text-sm tracking-normal text-center">12/31/2021</td>
            <td class="p-2 text-sm tracking-normal text-center">984.00</td>
            <td class="p-2 text-sm tracking-normal text-center">328.00</td>
            <td class="p-2 text-sm tracking-normal text-center">1,312.00</td>
            <td class="p-2 text-sm tracking-normal text-center">88.56</td>
            <td class="p-2 text-sm tracking-normal text-center">895.44</td>
            <td class="p-2 text-sm tracking-normal text-center">179.09</td>
            <td class="p-2 text-sm tracking-normal text-center">267.65</td>
            <td class="p-2 text-sm tracking-normal text-center">1,044.35</td>
          </tr>

          <tr class="flex flex-col md:flex-row bg-blue-100">
            <td class="p-2 text-sm tracking-normal text-center">1</td>
            <td class="p-2 text-sm tracking-normal text-center">4137497</td>
            <td class="p-2 text-sm tracking-normal text-center">MASANGYA</td>
            <td class="p-2 text-sm tracking-normal text-center">ALLYN</td>
            <td class="p-2 text-sm tracking-normal text-center">I</td>
            <td class="p-2 text-sm tracking-normal text-center">T III</td>
            <td class="p-2 text-sm tracking-normal text-center">6/26/2006</td>
            <td class="p-2 text-sm tracking-normal text-center">29,550.00</td>
            <td class="p-2 text-sm tracking-normal text-center">29,878.00</td>
            <td class="p-2 text-sm tracking-normal text-center">328.00</td>
            <td class="p-2 text-sm tracking-normal text-center">10/1/2021</td>
            <td class="p-2 text-sm tracking-normal text-center">12/31/2021</td>
            <td class="p-2 text-sm tracking-normal text-center">984.00</td>
            <td class="p-2 text-sm tracking-normal text-center">328.00</td>
            <td class="p-2 text-sm tracking-normal text-center">1,312.00</td>
            <td class="p-2 text-sm tracking-normal text-center">88.56</td>
            <td class="p-2 text-sm tracking-normal text-center">895.44</td>
            <td class="p-2 text-sm tracking-normal text-center">179.09</td>
            <td class="p-2 text-sm tracking-normal text-center">267.65</td>
            <td class="p-2 text-sm tracking-normal text-center">1,044.35</td>
          </tr>
        </tbody>


      </table>
    </div>

  </section>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
};
</script>
