<script>

    let users = [
        {
            ho_ten: "Nghiem Duong Hung",
            gioi_tinh: "Nam"
        },
        {
            ho_ten: "Nghiem Duong Hung 1",
            gioi_tinh: "Nam"
        },{
            ho_ten: "Nghiem Duong Hung 2 ",
            gioi_tinh: "Nam"
        },
        {
            ho_ten: "Nghiem Duong Hung3",
            gioi_tinh: "Nam"
        }
    ]
</script>

<table>
    <thead>
        <th>STT</th>
        <th>Ho va Ten</th>
        <th>Gioi Tinh</th>
    </thead>
    <tbody>
        {#each users as user, index (index)}
            <tr>
                <td>index</td>
                <td>{user.ho_ten}</td>
                <td>{user.gioi_tinh}</td>
            </tr>
        {/each}
    </tbody>
</table>